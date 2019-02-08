[English](./README.md) | 简体中文
# android
**简OS 开放源代码项目**

## 同步
```bash
# 初始化本地存储库
repo init -u https://github.com/JianSource/android -b master

# 同步
repo sync -c -j4 --force-sync --no-clone-bundle --no-tags
```

## 编译
```bash
# 设置环境
$ . build/envsetup.sh

# 选择一个目标
$ lunch aosp_$device-userdebug

# 编译代码
$ mka bacon -j4
```

© 版权 2018-2019 简OS。保留所有权利。
