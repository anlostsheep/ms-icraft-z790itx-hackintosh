# 铭瑄 MS-iCraft Z790ITX WIFI Hackintosh

> 黑苹果 EFI 配置说明



## 硬件配置

| 硬件 | 型号                                         | 官网地址                                                     |
| ---- | -------------------------------------------- | ------------------------------------------------------------ |
| CPU  | Intel i5-14600KF                             | [英特尔® 酷睿™ i5 处理器 14600KF]([Intel® Core™ i5 Processors (14th gen)](https://www.intel.cn/content/www/cn/zh/ark/products/series/236175/intel-core-i5-processors-14th-gen.html)) |
| 主板 | MS-iCraft Z790ITX WIFI                       | [MS-iCraft Z790ITX WIFI](https://www.maxsun.com.cn/2023/0331/5953.html) |
| 内存 | 金百达（KINGBANK）48GB(24GBX2)套装 DDR5 6800 | null                                                         |
| 显卡 | AMD RX6950XT 公版                            | [Radeon™ RX 6950 XT Desktop Graphics Card](https://www.amd.com/zh-cn/products/graphics/desktops/radeon/6000-series/amd-radeon-rx-6950-xt.html) |
| 硬盘 | 凯侠 SD10 1TB                                | nul                                                          |
| 网卡 | Intel AX211                                  | null                                                         |



## 主板 BIOS 设置

- 高级 -> CPU 设置 -> `CFG Lock` :  `Disabled`
- 高级 -> PCH 设置 -> `VT-d` : `disabled`
- 高级 -> PCH 设置 -> `大于4G解码` : `enable`
- 高级 -> PCH 设置 -> `resizeBar` : `enable`
- 启动 -> 快速启动 : `disabled`
- 启动 -> 安全启动 : `disabled`



## 安装系统版本

**macOS Sequoia 15.x**



## 系统功能

### CPU 睿频

![CPU睿频](https://cdn.jsdelivr.net/gh/anlostsheep/infinity-images@master/uPic/2025/{monty}/07/PixPin_2025-08-07_23-52-50.png)

### 显卡 Genbanch 6

**metal**

![metal](https://cdn.jsdelivr.net/gh/anlostsheep/infinity-images@master/uPic/2025/{monty}/08/PixPin_2025-08-08_00-04-29.png)



### 声卡

`Layout Id = 66`

![声卡](https://cdn.jsdelivr.net/gh/anlostsheep/infinity-images@master/uPic/2025/{monty}/08/PixPin_2025-08-08_00-11-53.png)



### 无线网卡

![无线网卡](https://cdn.jsdelivr.net/gh/anlostsheep/infinity-images@master/uPic/2025/{monty}/08/PixPin_2025-08-08_00-13-23.png)

### 有线网卡

![有线网卡](https://cdn.jsdelivr.net/gh/anlostsheep/infinity-images@master/uPic/2025/{monty}/08/PixPin_2025-08-08_00-14-23.png)

### USB 定制

> usb 定制可以先开启 `XhciPortLimit=true` 进入系统后再定制，我这里的定制机箱为联力 A4H2O

![usb](https://cdn.jsdelivr.net/gh/anlostsheep/infinity-images@master/uPic/2025/{monty}/08/PixPin_2025-08-08_00-15-31.png)



## 外观

![windows](https://cdn.jsdelivr.net/gh/anlostsheep/infinity-images@master/uPic/2025/{monty}/08/IMG_9048.jpg)



![macos](https://cdn.jsdelivr.net/gh/anlostsheep/infinity-images@master/uPic/2025/{monty}/08/IMG_8938.jpg)



## 其他功能

- [ ] 隔空投送
- [ ] 随航
- [ ] 通用控制
- [x] 睡眠
- [x] 蓝牙
- [x] WIFI



## 独立显卡的仿冒

仿冒有多种方式，参照我给出的此篇文章可以给 `AMD RX 6x50XT` 系列仿冒，但 `device-id` 不同需要注意
[**关于 RX 6x50 XT 显卡使用 WEG 加仿冒方式还是 NootRX 的问题**](https://bbs.pcbeta.com/viewthread-2035838-1-1.html)

