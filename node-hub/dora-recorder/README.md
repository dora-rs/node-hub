# dora-recorder

dora data recording in Apache Arrow IPC format

## Adding to existing graph

```yaml
- id: dora-recorder
  path: path-to-dora-recorder/target/release/dora-recorder
  inputs:
    image: webcam/image
    lidar: lidar/pointcloud
    # ... (any input which is going to be logged)
```

## Output Files

**Format**: Arrow IPC file
**Path**: `record-session_<TIMESTAMP>/type-<TYPE_ID>.arrow` (TYPE-ID starts from 1 and ends at the total number of `data_types` of the message to be recorded)

**Columns**:
- payload_list: List, containing the input messages
- timestamp: u64, representing the timestamp in [Unique Hybrid Logical Clock time](https://github.com/atolab/uhlc-rs)
- topic: id

Example:

```json
------------------------------------------------
| payload_list |      timestamp      |  topic  |
------------------------------------------------
| <Arrow Msg>  | 7651893987555135264 | x-topic |
------------------------------------------------
| <Arrow Msg>  | 7651894009906043616 | y-topic |
------------------------------------------------
...
```

## Limitations

**Message Size Cap**: Any single incoming message larger than **16 MB** will be dropped. This is due to the node's internal 16 MB semaphore-controlled memory queue, which is designed to prevent Out-Of-Memory (OOM) crashes under high-throughput conditions. If you need to record larger messages, consider adjusting the buffer size(`buffer_size` variable) in the source code.
