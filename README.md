# OpenCV build script for Jetson Orin

This script builds OpenCV from source on Tegra (Nano, NX, AGX, etc.).

Related thread on Nvidia developer forum 
[here](https://devtalk.nvidia.com/default/topic/1051133/jetson-nano/opencv-build-script/).

[How it Works](https://wiki.debian.org/QemuUserEmulation)

## Usage:
```shell
./build_opencv.sh
```

## Specifying an OpenCV version (git branch)
```shell
./build_opencv.sh 4.8.4
```

This is only slightly modified fork for ease of use on jetson orin
