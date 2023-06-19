



# Huawei-Matebook-X-Pro-2018

Huawei-Matebook-X-Pro-2018 黑苹果

## 电脑配置

| 配置        | 型号                                          | 说明                                    |
| ----------- | --------------------------------------------- | --------------------------------------- |
| CPU         | Intel® i5 8250U                               |                                         |
| 屏幕        | 3000 x 2000 (13.9 英寸) 60hz                  |                                         |
| 显卡        | Intel® UHD Graphics 620+NVIDIA® GeForce MX150 | 使用Intel® UHD Graphics 620             |
| 内存        | LPDDR4 2133MHz 8G                             |                                         |
| SSD         | M.2 256G                                      |                                         |
| WiFi + 蓝牙 | Intel® 8265                                   | macOS Sonoma WIFI需搭配包内HeliPort使用 |
| 声卡        | Realtek® ALC256                               |                                         |

### 更新说明

2023.06.19

- 添加支持Windows+macOS双系统的MOD版本

2023.06.18

- 重新更新Kext，进一步精简Kext文件
- 更新蓝牙补丁 [@zxystd](https://github.com/zxystd/BrcmPatchRAM)
- 更新一些其他小细节

2023.06.16

- 同步更新至Opencore 0.9.3
- 更新Kext
- 修复Ventura 13.4蓝牙问题 [@zxystd](https://github.com/zxystd/BrcmPatchRAM)
- 修复Ventura 13.4触控板、触摸问题 [@VoodooI2C](https://github.com/VoodooI2C/VoodooI2C)
- 关闭啰嗦模式
- 修正config.plist错误、调整Kext
- 支持在线增量升级
- 更新主题

### **时间问题**

Windows+macOS双系统时间不对，Windows下导入下面的注册表文件即可

[打开时间同步](https://github.com/Hakarikyo/Huawei-Matebook-X-Pro-2018/blob/main/Time/%E6%97%B6%E9%97%B4%E5%90%8C%E6%AD%A5%E5%BC%80WinUTCOn.reg)

[关闭时间同步](https://github.com/Hakarikyo/Huawei-Matebook-X-Pro-2018/blob/main/Time/%E6%97%B6%E9%97%B4%E5%90%8C%E6%AD%A5%E5%85%B3WinUTCOff.reg)（还原注册表更改，一般不用）

### **正常功能**

- Intel® 8265无线网卡+蓝牙（Ventura 13.4可开关）
- Intel® UHD Graphics 620
- 板载Realtek® ALC256声卡
- 快捷调节背光（F1 [亮度降低] - F2 [亮度升高]）
- 快捷调节音量（F4 [静音] - F5 [降低音量] - F6 [提高音量]）
- 支持传感器
- 触控板、触摸屏
- 带 USB Type-C 热插拔的雷电口
- 摄像头
- 支持睡眠、唤醒（如有问题，使用Hackintool选择电源选项卡点击下方的螺丝刀图标即可修复）
- 定制的OC引导界面（引导界面按空格可以出现重置Nvram的功能，双系统按Ctrl+回车可以设置默认启动项）

### **不正常功能**

❌ 指纹（无解）

❌ NVIDIA® GeForce MX150（无解）

<h3>预览图片</h3>

<img src="https://github.com/Hakarikyo/Huawei-Matebook-X-Pro-2018/blob/main/Picture/Ventura_13.4.png?raw=true" alt="Ventura_13.4" style="zoom: 33%;" />

### BIOS设置

* 安全设置-安全启动【禁用】
* 安全设置-安全芯片【禁用】
* 雷电设备-安全等级【No Security】
* 高级设置-PXE设备【禁用】
* 高级设置-指纹【禁用】

### 兼容版本

| 版本                       | 支持                                                         | 下载                                                         | BUG    |
| -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| macOS Sonoma Beta          | ✅ （WIFI需搭配压缩包内HeliPort使用 [@zxystd](https://github.com/OpenIntelWireless/HeliPort)） | [地址](https://github.com/Hakarikyo/Huawei-Matebook-X-Pro-2018/releases) | 待测试 |
| macOS Ventura 13.4（13.5） | ✅                                                            | [地址](https://github.com/Hakarikyo/Huawei-Matebook-X-Pro-2018/releases) | 待反馈 |

<h3>参考对象</h3>

https://github.com/profzei/Matebook-X-Pro-2018

https://github.com/tlefko/Huawei-Matebook-X-Pro-Ventura
