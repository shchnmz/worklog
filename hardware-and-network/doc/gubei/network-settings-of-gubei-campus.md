# 古北校区网络设置

## VLAN
* 基于 H3C 路由器的 LAN 口分配的VLAN

| VLAN ID | 用途 |
| :--: | :--: |
| 1 | 电脑，UBNT UAP，服务器，打印机 |
| 2 | 手机，移动设备 |
| 3 | 摄像头，硬盘录像机 |

## 打印机和服务器

| 设备 | MAC | IP | 备注 |
| :--: | :--: | :--: | :--: |
| Canon 2204n 打印机 | 40:9F:38:30:78:B8 | 192.168.1.66 | 静态 IP |
| Canon G3800 喷墨打印机 | 00:BB:C1:98:27:30 | 192.168.1.44 | DHCP，驱动使用 Canon BJ Network Port，[WLAN Configuration of Canon PIXMA G3800 Printer](https://github.com/northbright/Notes/blob/master/Software/driver/canon/wlan-configuration-of-canon-pixma-g3800-printer/wlan-configuration-of-canon-pixma-g3800-printer.md) |
| HP z228 服务器 | 50:65:F3:2C:8D:6B | 192.168.1.97 | 静态 IP | 

## 摄像头和硬盘录像机
* 使用 VLAN ID: 3

| 设备 | MAC | 静态 IP |
| :--: | :--: | :--: |
| 海康威视硬盘录像机 | 54:C4:15:D2:9D:95 | 192.168.3.70 |

## UBNT UAP and Unifi Controller

| 位置 | MAC | 静态 IP |
| :--: | :--: | :--: |
| 1楼前台 | f0:9f:c2:d6:55:65 | 192.168.1.6 |
| 1楼机房 | f0:9f:c2:d6:55:03 | 192.168.1.4 |
| 206 | f0:9f:c2:d6:54:f1 | 192.168.1.2 |
| 2楼办公室门口 | f0:9f:c2:d6:55:10 | 192.168.1.3 |
| 2楼领导办公室阁楼夹层 | f0:9f:c2:d6:55:21 | 192.168.1.5 |

* Unifi Controller
  * 迁移至 联想 E480 笔记本
