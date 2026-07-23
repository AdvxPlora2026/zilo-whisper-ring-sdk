Apple 不公开 BLE MAC 地址，Swift 版使用 CBPeripheral.identifier UUID。
iOS 需配置 NSBluetoothAlwaysUsageDescription；macOS 沙盒应用需启用 Bluetooth entitlement。
macOS 可用 ffmpeg 解码 Speex；iOS 需注入原生 SpeexDecoder。