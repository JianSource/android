English | [简体中文](./README_CN.md)
# android
**JianOS Open-Source Project**

## Sync
```bash
# Initialize local repository
repo init -u https://github.com/PixelExperience/android -b master

# Sync
repo sync -c -j4 --force-sync --no-clone-bundle --no-tags
```

## Build
```bash
# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -j4
```

© Copyright 2018-2019 JianOS. All rights reserved.
