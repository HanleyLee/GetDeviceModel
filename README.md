# HLDeviceKit

## 功能

返回当前iOS 设备的型号(含: iPhone, iPad, iPod, Apple TV, Simulator)

## 使用方式

1. 将本项目的 [UIDevice+Exten.swift](https://github.com/HanleyLee/HLDeviceKit/blob/master/UIDevice%2BExten.swift) 下载后放入 Xcode 工程中任意位置。

2. Xcode 工程中一行代码将当前设备名赋值至变量 `deviceName`(可以将变量命名为任意值)

```swift
let deviceName = UIDevice.current.name
```

## 开源许可

本仓库的所有代码基于 [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0) 进行分发与使用. 协议全文见 [LICENSE](https://github.com/HanleyLee/HLDeviceKit/blob/master/LICENSE) 文件.

Copyright 2019-2020 HanleyLee

---

欢迎使用, 有任何 bug, 希望给我提 issues. 作者会根据最新的设备型号保持更新, 如果对你有用的话请标记一颗星星 ⭐️

