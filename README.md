# common-android12-5.10-KernelSU
GKI for android12-5.10 with KernelSU



# How to build
```
sudo apt-get update -y
sudo apt-get install -y ccache lzop cpio bzip2 zip flex bison gperf

Without LTO:
BUILD_CONFIG=common/build.config.gki.aarch64 build/build.sh

LTO:
LTO=thin BUILD_CONFIG=common/build.config.gki.aarch64 build/build.sh
```
