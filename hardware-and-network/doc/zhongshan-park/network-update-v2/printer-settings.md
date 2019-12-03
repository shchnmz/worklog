# 中山公园校区打印机设置

## 2楼
| ID / 型号 | 位置 | 类型 | IP | 是否静态IP | 连接方式 |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 2F-01-canon-2204 | 2楼素描办公室 | 黑白激光 | 10.0.10.4 | Yes | 有线 |
| 2F-02-canon-g3800 | 2楼素描办公室（墙上隔板）| 彩色喷墨 |10.0.10.82 | No| 无线 |
| 2F-03-epson-6168 | 2楼素描办公室（交换机旁） | 彩色喷墨 |10.0.10.5 |Yes | 无线 |
| 2F-04-epson-6168 | 2楼会议室 | 彩色喷墨 | 10.0.10.6 |Yes | 无线 |

## 3楼
| ID / 型号 | 位置 | 类型 | IP | 是否静态IP | 连接方式 |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 3F-01-canon-g3800 | 3楼幼儿办公室| 彩色喷墨 |10.0.10.96 | No| 无线 |
| 3F-02-epson-6168 | 3楼幼儿办公室（交换机旁） | 彩色喷墨 |10.0.10.7 |Yes | 无线 |
| 3F-03-canon-g3800 | 3楼基础大办公室| 彩色喷墨 |10.0.10.97 | No| 无线 |
| 2F-04-epson-6168 | 3楼基础大办公室 | 彩色喷墨 | 10.0.10.9 |Yes | 无线 |

## 3楼校长室
| ID / 型号 | 位置 | 类型 | IP | 是否静态IP | 连接方式 |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 3F-校长室-canon-ts8280(没有安装到共享服务器) | 3楼校长室 | 彩色喷墨 |10.0.10.8 |Yes | 无线 |

## 打印机连接的VLAN
* VLAN: 10
* DHCP
  * IP Pool: 10.0.10.0 / 24
  * Forbidden IP Range: 10.0.10.1 - 10.0.10.20
  * Gateway: 10.0.10.1
  * DNS: 10.0.100.2

## 打印机的型号和驱动，扫描程序

| 型号 | 打印机驱动文件 | 扫描程序 |
| :--: | :--: | :--: |
| Canon 2204n | iR2204MFDriverV2160W64ZH.exe | ToolBox4911mf18WinSC.exe |
| Canon G3800 | mp68-win-g3000-1_02-ea34_2.exe | [How to Scan with Canon G3800 Printer / Scanner](https://github.com/northbright/Notes/blob/master/Software/driver/canon/how-to-scan-with-canon-g3800-printer-scanner.md) |
| Epson L6168 | L6160_x64_261JAUsHomeExportAsiaML.exe | EpsonScan2_L6160_L6170_6400.exe |
