# Dora Node Hub

This hub contains useful pre-built nodes for Dora.

## Packages

> Feel free to modify this README with your own nodes so that it benefits the community.

| Type                          | Title                                                                                            | Support           | Description                                      | Downloads                                                                     | License                                                                    |
| ----------------------------- | ------------------------------------------------------------------------------------------------ | ----------------- | ------------------------------------------------ | ----------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| Camera                        | [PyOrbbeckSDK](https://github.com/dora-rs/node-hub/blob/main/dora-pyorbbecksdk)                  | 📐                 | Image and depth from Orbbeck Camera              | ![Downloads](https://img.shields.io/pypi/dm/dora-pyorbbecksdk?label=%20)      | ![License](https://img.shields.io/pypi/l/dora-pyorbbecksdk?label=%20)      |
| Camera                        | [PyRealsense](https://github.com/dora-rs/node-hub/blob/main/dora-pyrealsense)                    | Linux🆗 <br> Mac🛠️  | Image and depth from Realsense                   | ![Downloads](https://img.shields.io/pypi/dm/dora-pyrealsense?label=%20)       | ![License](https://img.shields.io/pypi/l/dora-pyrealsense?label=%20)       |
| Camera                        | [OpenCV Video Capture](https://github.com/dora-rs/node-hub/blob/main/opencv-video-capture)       | ✅                 | Image stream from OpenCV Camera                  | ![Downloads](https://img.shields.io/pypi/dm/opencv-video-capture?label=%20)   | ![License](https://img.shields.io/pypi/l/opencv-video-capture?label=%20)   |
| Camera                        | [Kornia V4L Capture](https://github.com/kornia/dora-nodes-hub/tree/main/kornia-v4l-capture)      | ✅                 | Video stream for Linux Camera (rust)             |                                                                               | ![License](https://img.shields.io/badge/license-Apache%202-blue)           |
| Camera                        | [Kornia GST Capture](https://github.com/kornia/dora-nodes-hub/tree/main/kornia-gst-capture)      | ✅                 | Video Capture using Gstreamer (rust)             |                                                                               | ![License](https://img.shields.io/badge/license-Apache%202-blue)           |
| Peripheral                    | [Keyboard](https://github.com/dora-rs/node-hub/blob/main/dora-keyboard)                          | ✅                 | Keyboard char listener                           | ![Downloads](https://img.shields.io/pypi/dm/dora-keyboard?label=%20)          | ![License](https://img.shields.io/pypi/l/dora-keyboard?label=%20)          |
| Peripheral                    | [Microphone](https://github.com/dora-rs/node-hub/blob/main/dora-microphone)                      | ✅                 | Audio from microphone                            | ![Downloads](https://img.shields.io/pypi/dm/dora-microphone?label=%20)        | ![License](https://img.shields.io/pypi/l/dora-microphone?label=%20)        |
| Peripheral                    | [PyAudio(Speaker)](https://github.com/dora-rs/node-hub/blob/main/dora-pyaudio)                   | ✅                 | Output audio from speaker                        | ![Downloads](https://img.shields.io/pypi/dm/dora-pyaudio?label=%20)           | ![License](https://img.shields.io/pypi/l/dora-pyaudio?label=%20)           |
| Actuator                      | [Feetech](https://github.com/dora-rs/dora-lerobot/blob/main/node-hub/feetech-client)             | 📐                 | Feetech Client                                   |                                                                               |                                                                            |
| Actuator                      | [Dynamixel](https://github.com/dora-rs/dora-lerobot/blob/main/node-hub/dynamixel-client)         | 📐                 | Dynamixel Client                                 |                                                                               |                                                                            |
| Chassis                       | [Agilex - UGV](https://github.com/dora-rs/node-hub/blob/main/dora-ugv)                           | 🆗                 | Robomaster Client                                | ![Downloads](https://img.shields.io/pypi/dm/dora-ugv?label=%20)               | ![License](https://img.shields.io/pypi/l/dora-ugv?label=%20)               |
| Chassis                       | [DJI - Robomaster S1](https://huggingface.co/datasets/dora-rs/dora-robomaster)                   | 📐                 | Robomaster Client                                |                                                                               |                                                                            |
| Chassis                       | [Dora Kit Car](https://github.com/dora-rs/node-hub/blob/main/dora-kit-car)                       | 🆗                 | Open Source Chassis                              | ![Downloads](https://img.shields.io/pypi/dm/dora-kit-car?label=%20)           | ![License](https://img.shields.io/pypi/l/dora-kit-car?label=%20)           |
| Arm                           | [Alex Koch - Low Cost Robot](https://github.com/dora-rs/dora-lerobot/blob/main/robots/alexk-lcr) | 📐                 | Alex Koch - Low Cost Robot Client                |                                                                               |                                                                            |
| Arm                           | [Lebai - LM3](https://github.com/dora-rs/dora-lerobot/blob/main/node-hub/lebai-client)           | 📐                 | Lebai client                                     |                                                                               |                                                                            |
| Arm                           | [Agilex - Piper](https://github.com/dora-rs/node-hub/blob/main/dora-piper)                       | 🆗                 | Agilex arm client                                | ![Downloads](https://img.shields.io/pypi/dm/dora-piper?label=%20)             | ![License](https://img.shields.io/pypi/l/dora-piper?label=%20)             |
| Robot                         | [Pollen - Reachy 1](https://github.com/dora-rs/dora-lerobot/blob/main/node-hub/dora-reachy1)     | 📐                 | Reachy 1 Client                                  |                                                                               |                                                                            |
| Robot                         | [Pollen - Reachy 2](https://github.com/dora-rs/node-hub/blob/main/dora-reachy2)                  | 🆗                 | Reachy 2 client                                  | ![Downloads](https://img.shields.io/pypi/dm/dora-reachy2?label=%20)           | ![License](https://img.shields.io/pypi/l/dora-reachy2?label=%20)           |
| Robot                         | [Trossen - Aloha](https://github.com/dora-rs/dora-lerobot/blob/main/robots/aloha)                | 📐                 | Aloha client                                     |                                                                               |                                                                            |
| Voice Activity Detection(VAD) | [Silero VAD](https://github.com/dora-rs/node-hub/blob/main/dora-vad)                             | ✅                 | Silero Voice activity detection                  | ![Downloads](https://img.shields.io/pypi/dm/dora-vad?label=%20)               | ![License](https://img.shields.io/pypi/l/dora-vad?label=%20)               |
| Speech to Text(STT)           | [Whisper](https://github.com/dora-rs/node-hub/blob/main/dora-distil-whisper)                     | ✅                 | Transcribe audio to text                         | ![Downloads](https://img.shields.io/pypi/dm/dora-distil-whisper?label=%20)    | ![License](https://img.shields.io/pypi/l/dora-distil-whisper?label=%20)    |
| Object Detection              | [Yolov8](https://github.com/dora-rs/node-hub/blob/main/dora-yolo)                                | ✅                 | Object detection                                 | ![Downloads](https://img.shields.io/pypi/dm/dora-yolo?label=%20)              | ![License](https://img.shields.io/pypi/l/dora-yolo?label=%20)              |
| Segmentation                  | [SAM2](https://github.com/dora-rs/node-hub/blob/main/dora-sam2)                                  | Cuda✅ <br> Metal🛠️ | Segment Anything                                 | ![Downloads](https://img.shields.io/pypi/dm/dora-sam2?label=%20)              | ![License](https://img.shields.io/pypi/l/dora-sam2?label=%20)              |
| Large Language Model(LLM)     | [Qwen2.5](https://github.com/dora-rs/node-hub/blob/main/dora-qwen)                               | ✅                 | Large Language Model using Qwen                  | ![Downloads](https://img.shields.io/pypi/dm/dora-qwen?label=%20)              | ![License](https://img.shields.io/pypi/l/dora-qwen?label=%20)              |
| Vision Language Model(VLM)    | [Qwen2.5-vl](https://github.com/dora-rs/node-hub/blob/main/dora-qwen2-5-vl)                      | ✅                 | Vision Language Model using Qwen2.5 VL           | ![Downloads](https://img.shields.io/pypi/dm/dora-qwen2-5-vl?label=%20)        | ![License](https://img.shields.io/pypi/l/dora-qwen2-5-vl?label=%20)        |
| Vision Language Model(VLM)    | [InternVL](https://github.com/dora-rs/node-hub/blob/main/dora-internvl)                          | 🆗                 | InternVL is a vision language model              | ![Downloads](https://img.shields.io/pypi/dm/dora-internvl?label=%20)          | ![License](https://img.shields.io/pypi/l/dora-internvl?label=%20)          |
| Vision Language Action(VLA)   | [RDT-1B](https://github.com/dora-rs/node-hub/blob/main/dora-rdt-1b)                              | 🆗                 | Infer policy using Robotic Diffusion Transformer | ![Downloads](https://img.shields.io/pypi/dm/dora-rdt-1b?label=%20)            | ![License](https://img.shields.io/pypi/l/dora-rdt-1b?label=%20)            |
| Translation                   | [ArgosTranslate](https://github.com/dora-rs/node-hub/blob/main/dora-argotranslate)               | 🆗                 | Open Source translation engine                   | ![Downloads](https://img.shields.io/pypi/dm/dora-argotranslate?label=%20)     | ![License](https://img.shields.io/pypi/l/dora-argotranslate?label=%20)     |
| Translation                   | [Opus MT](https://github.com/dora-rs/node-hub/blob/main/dora-opus)                               | 🆗                 | Translate text between language                  | ![Downloads](https://img.shields.io/pypi/dm/dora-opus?label=%20)              | ![License](https://img.shields.io/pypi/l/dora-opus?label=%20)              |
| Text to Speech(TTS)           | [Kokoro TTS](https://github.com/dora-rs/node-hub/blob/main/dora-kokoro-tts)                      | ✅                 | Efficient Text to Speech                         | ![Downloads](https://img.shields.io/pypi/dm/dora-kokoro-tts?label=%20)        | ![License](https://img.shields.io/pypi/l/dora-kokoro-tts?label=%20)        |
| Recorder                      | [Llama Factory Recorder](https://github.com/dora-rs/node-hub/blob/main/llama-factory-recorder)   | 🆗                 | Record data to train LLM and VLM                 | ![Downloads](https://img.shields.io/pypi/dm/llama-factory-recorder?label=%20) | ![License](https://img.shields.io/pypi/l/llama-factory-recorder?label=%20) |
| Recorder                      | [LeRobot Recorder](https://github.com/dora-rs/dora-lerobot/blob/main/node-hub/lerobot-dashboard) | 📐                 | LeRobot Recorder helper                          |                                                                               |                                                                            |
| Visualization                 | [Plot](https://github.com/dora-rs/node-hub/blob/main/opencv-plot)                                | ✅                 | Simple OpenCV plot visualization                 | ![Downloads](https://img.shields.io/pypi/dm/dora-yolo?label=%20)              | ![License](https://img.shields.io/pypi/l/opencv-plot?label=%20)            |
| Visualization                 | [Rerun](https://github.com/dora-rs/node-hub/blob/main/dora-rerun)                                | ✅                 | Visualization tool                               | ![Downloads](https://img.shields.io/pypi/dm/dora-rerun?label=%20)             | ![License](https://img.shields.io/pypi/l/dora-rerun?label=%20)             |
| Simulator                     | [Mujoco](https://github.com/dora-rs/dora-lerobot/blob/main/node-hub/mujoco-client)               | 📐                 | Mujoco Simulator                                 |                                                                               |                                                                            |
| Simulator                     | [Carla](https://github.com/dora-rs/dora-drives)                                                  | 📐                 | Carla Simulator                                  |                                                                               |                                                                            |
| Simulator                     | [Gymnasium](https://github.com/dora-rs/dora-lerobot/blob/main/gym_dora)                          | 📐                 | Experimental OpenAI Gymnasium bridge             |                                                                               |                                                                            |
| Image Processing              | [Kornia Sobel Operator](https://github.com/kornia/dora-nodes-hub/tree/main/kornia-imgproc-sobel) | ✅                 | Kornia image processing Sobel operator (rust)    |                                                                               | ![License](https://img.shields.io/badge/license-Apache%202-blue)           |


# Python

## Add a new python node

- To work on a new node, start by:

```bash
cd node-hub
dora new your-node-name --lang python --kind node
cd ./your-node-name
uv venv --seed -p 3.11
uv pip install -e . # Install
uv run ruff check . --fix # Format
uv run ruff check . # Lint
uv run pytest . # Test
```

- To add a python dependency just do:

```bash
uv add numpy # for example
```

> The package is then added to your `pyproject.toml`

- Modify the code within `main.py` in your liking.

- Create a PR and let the CI/CD run test on it 🙋

## Structure

The structure of the node hub is as follows (please use the same structure if you need to add a new node):

```
node-hub/
└── your-node/
    ├── README.md
    ├── your-node
    │   ├── __init__.py
    │   ├── __main__.py
    │   └── main.py
    ├── pyproject.toml
    └── tests
        └── test_<your-node>.py
```

The idea is to make a `pyproject.toml` file that will install the required dependencies for the node **and** attach main
function of the node inside a callable script in your environment.

To do so, you will need to add a `main` function inside the `main.py` file.

```python
def main():
    pass
```

And then you will need to adapt the following `pyproject.toml` file:

```toml
[project]
name = "[name of the node e.g. video-encoder, with '-' to replace spaces]"
version = "0.1"
authors = [{ name = "[Pseudo/Name]", email = "[email]" }]
description = "Dora Node for []"
readme = "README.md"
license = { text = "MIT" }

dependencies = [
    "dora-rs >= 0.3.8",
]

[project.scripts]
[name of the node with '-' to replace spaces] = "[name of the node with '_' to replace spaces].main:main"

[tool.ruff.lint]
extend-select = [
  "D",    # pydocstyle
  "UP",   # Ruff's UP rule
  "PERF", # Ruff's PERF rule
  "RET",  # Ruff's RET rule
  "RSE",  # Ruff's RSE rule
  "NPY",  # Ruff's NPY rule
  "N",    # Ruff's N rule
  "I",    # Ruff's I rule
]
```

Finally, the README.md file should explicit all inputs/outputs of the node and how to configure it in the YAML file.

## Example

```toml
[project]
name = "opencv-plot"
version = "0.1"
authors = [
    "Haixuan Xavier Tao <tao.xavier@outlook.com>",
    "Enzo Le Van <dev@enzo-le-van.fr>"
]
description = "Dora Node for plotting data with OpenCV"
readme = "README.md"
license = { text = "MIT" }
requires-python = ">=3.7"

dependencies = [
    "dora-rs >= 0.3.8",
]
[dependency-groups]
dev = ["pytest >=8.1.1", "ruff >=0.9.1"]

[project.scripts]
opencv-plot = "opencv_plot.main:main"

[tool.ruff.lint]
extend-select = [
  "D",    # pydocstyle
  "UP",   # Ruff's UP rule
  "PERF", # Ruff's PERF rule
  "RET",  # Ruff's RET rule
  "RSE",  # Ruff's RSE rule
  "NPY",  # Ruff's NPY rule
  "N",    # Ruff's N rule
  "I",    # Ruff's I rule
]
```
## Adding git dependency
- If a git repository is added as submodule. Proper path should be added in `pyproject.toml` inorder to make sure that linting and testing are exempted for that dependency.
- A very good example of how this can be done is as follows

Correct approach:
```toml
[tool.ruff]
exclude = ["dora_magma/Magma"]

[tool.black]
extend.exclude = "dora_magma/Magma"
```
Incorrect Approach:
```toml
[tool.ruff]
exclude = ["dora-magma/dora_magma/Magma"]

[tool.black]
extend.exclude = "dora_magma/Magma"
```
##### Note:
- `dora-magma` is root folder of the node.

# Rust

## Add a new rust node

```bash
cd node-hub
dora new your-node-name --lang rust --kind node
cd ./your-node-name
```

## Steps Before Building

- Before building the node, make sure to add your node to the workspace members list in the root `Cargo.toml` file:

```
[workspace]
members = [
...
"node-hub/your-node-name"
]
```

- Also change the `Cargo.toml` file in your node to use the workspace version of dora-node-api:

```
[dependencies]
dora-node-api = { workspace = true }
```

## Structure

The structure of the node hub for Rust is as follows (please use the same structure if you need to add a new node):

```
node-hub/
└── your-node/
    ├── Cargo.toml
    ├── README.md
    └── src/
           └── main.rs
```

The README.md file should explicit all inputs/outputs of the node and how to configure it in the YAML file.

## License

This project is licensed under Apache-2.0. Check out [NOTICE.md](../NOTICE.md) for more information.
