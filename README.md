# HLDeviceKit

![GitHub last commit](https://img.shields.io/github/last-commit/hanleylee/HLDeviceKit)
![language-swift](https://img.shields.io/badge/language-swift-yellow)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/HanleyLee/HLDeviceKit)
![Cocoapods](https://img.shields.io/cocoapods/v/HLDeviceKit)
![GitHub](https://img.shields.io/github/license/hanleylee/HLDeviceKit)

返回当前 Apple 设备(含: iPhone, iPad, iPod, Apple TV, Simulator)的信息(含型号等)

## 安装

- Cocoapods

    ```bash
    pod `HLDeviceKit`
    ```

## Usage

Xcode 工程中一行代码将当前设备名赋值至变量 `deviceName`(可以将变量命名为任意值)

```swift
let deviceName = HLDevice.now.modelName
```

## 开源许可

本仓库的所有代码基于 [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0) 进行分发与使用. 协议全文见 [LICENSE](https://github.com/HanleyLee/HLDeviceKit/blob/master/LICENSE) 文件.

Copyright 2019-2020 HanleyLee

---

欢迎使用, 有任何 bug, 希望给我提 issues. 作者会根据最新的设备型号保持更新, 如果对你有用的话请标记一颗星星 ⭐️

