Follow Rasberry Pi AI Camera/AI HAT+ documentation to set up hardware, firmware, and software

Test Camera configuration using:
```markdown
rpicam-hello -t 0s --post-process-file /usr/share/rpi-camera-assets/imx500_posenet.json --viewfinder-width 1920 --viewfinder-height 1080 --framerate 30

The Hailo-8 chip requires models to be ran in a .hef compiled format. I tried running a .onnx posenet model on the system, but only the CPU was available for computing.
Download the Hailo software suite from the following link on a compatible system:
'''markdown
https://hailo.ai/developer-zone/software-downloads/
