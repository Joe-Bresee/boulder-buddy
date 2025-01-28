# Raspberry Pi AI Camera/AI HAT+ Setup

Follow the Raspberry Pi AI Camera/AI HAT+ documentation to set up hardware, firmware, and software.

## Test Camera Configuration

Test the camera configuration using the following command:

```bash
rpicam-hello -t 0s --post-process-file /usr/share/rpi-camera-assets/imx500_posenet.json --viewfinder-width 1920 --viewfinder-height 1080 --framerate 30
