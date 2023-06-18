



# Huawei-Matebook-X-Pro-2018

黑苹果 Huawei-Matebook-X-Pro-2018

## 配置

| 配置        | 型号                                           | 说明                              |
| ----------- | ---------------------------------------------- | --------------------------------- |
| CPU         | Intel i5 8250U                                 |                                   |
| 屏幕        | 3000 x 2000 (13.9 英寸) 60hz                   |                                   |
| 显卡        | NVIDIA GeForce MX150/Intel(R) UHD Graphics 620 | 使用Intel(R) UHD Graphics 620     |
| 内存        | LPDDR4 2133MHz 8G                              |                                   |
| SSD         | M.2 256G                                       |                                   |
| WiFi + 蓝牙 | Intel 8265                                     | Sonoma WIFI需搭配包内HeliPort使用 |
| 声卡        | Realtek® ALC256                                |                                   |

### 更新

2023.06.18

- 重新更新Kext，进一步精简Kext文件
- 修复一些其他小问题

2023.06.16

- 同步更新至Opencore 0.9.3

- 更新Kext

- 修复Ventura 13.4蓝牙问题 [@zxystd](https://github.com/zxystd/BrcmPatchRAM)

- 修复Ventura 13.4触控板、触摸问题 [@VoodooI2C](https://github.com/VoodooI2C/VoodooI2C)

- 关闭啰嗦模式

- 修正config.plist错误、调整Kext

- 支持在线增量升级

- 更新主题


<h3>预览</h3>

<img src="https://github.com/Hakarikyo/Huawei-Matebook-X-Pro-2018/blob/main/Picture/Ventura_13.4.png?raw=true" alt="Ventura_13.4" style="zoom: 33%;" />

### BIOS

* 安全设置-安全启动【禁用】
* 安全设置-安全芯片【禁用】
* 雷电设备-安全等级【No Security】
* 高级设置-PXE设备【禁用】
* 高级设置-指纹【禁用】

### 兼容

| 版本                       | 支持                                                         | 下载                                                         | BUG    |
| -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| macOS Sonoma Beta          | ✅ （WIFI需搭配压缩包内HeliPort使用 [@zxystd](https://github.com/OpenIntelWireless/HeliPort)） | [地址](https://github.com/Hakarikyo/Huawei-Matebook-X-Pro-2018/releases) | 待测试 |
| macOS Ventura 13.4（13.5） | ✅                                                            | [地址](https://github.com/Hakarikyo/Huawei-Matebook-X-Pro-2018/releases) | 待反馈 |

### 不兼容硬件

❌ 指纹

❌ NVIDIA GeForce MX150


<h3>参考：</h3>

https://github.com/profzei/Matebook-X-Pro-2018

https://github.com/tlefko/Huawei-Matebook-X-Pro-Ventura
