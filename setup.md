# Raspberry Pi AI Camera/AI HAT+ Setup

Follow the Raspberry Pi AI Camera/AI HAT+ documentation to set up hardware, firmware, and software.

## Test Camera Configuration

Test the camera configuration using the following command:

  ```
  rpicam-hello -t 0s --post-process-file /usr/share/rpi-camera-assets/imx500_posenet.json --viewfinder-width 1920 --viewfinder-height 1080 --framerate 30

```
## Hailo-8 Chip Setup

The Hailo-8 chip requires models to be run in a `.hef` compiled format. I tried running a `.onnx` posenet model on the system, but only the CPU was available for computing.

To use the Hailo-8 chip with your models, download the Hailo software suite from the following link on a compatible system:

[Download Hailo Software Suite](https://hailo.ai/developer-zone/software-downloads/)

There you can find various resources to compile models in hef format, their model zoo, and more.

Or, I cloned their examples repo to access the models already in hef format:
[Hailo Examples repo](https://github.com/hailo-ai/hailo-rpi5-examples?tab=readme-ov-file)
