# 威宁校区网络改造以及设置

## VLAN
使用H3C ER3260路由器的基于端口的VLAN

| VLAN ID | IP | Description | H3C Router LAN ID |
| :---: | :---: | :---: | :---: |
| 20 | 192.168.20.1 | UBNT Unifi Controller Wireless Network: chnmz | 2 |
| 30 | 192.168.30.1 | Network for Hikvision Cameras and Recorder | 3 |

## UBNT UAP的位置和设备信息

| MAC | 型号 | 位置 | 2.4 G信道 |  5G 信道 |
| :---: | :---: | :---: | :---: | :---: |
| f0:9f:c2:d6:55:97 | UAP AC Lite | 报名处 | 1 | 149 |
| 78:8a:a0:48:59:11 | UAP AC Lite | 1号教室 | 6 | 153 |
| 78:8a:20:48:56:ab | UAP AC Lite | 走廊从最西面数第1个 | 11 | 161 |
| 78:8a:20:70:22:df | UAP AC Lite | 走廊从最西面数第2个 | 1 | 149 |
| 78:8a:20:48:46:0b | UAP AC Lite | 教务处 | 6 | 153 |
| 78:8a:20:48:64:86 | UAP AC Lite | 走廊从最西面数第3个 | 11 | 161 |
| 78:8a:20:48:64:d6 | UAP AC Lite | 走廊从最西面数第4个 | 1 | 149 |
| 78:8a:20:48:58:b1 | UAP AC Lite | 财务室 | 6 | 153 |
| 78:8a:20:70:23:2a | UAP AC Lite | 领导办公室 | 11 | 161 |

## ER3260 DHCP 静态路由表

| MAC | IP | Description |
| :--: | :--: | :--: |
| 50:9A:4C:79:C5:67 | 192.168.1.2 | server |
| F8:0D:60:B9:4A:83 | 192.168.1.11 | Canon2204n-JW |
| 08:00:27:BF:26:4E | 192.168.1.40 | CentOS-x64-new |
| 2C:9E:FC:5D:57:52 | 192.168.1.12 | CanonMF4720_aj |
| 08:00:27:9D:91:7C | 192.168.1.5 | chnmz-ming800 |
| 70:5A:0F:47:8D:4F | 192.168.1.3 | z238-server |
| 00:BB:C1:70:69:50 | 192.168.1.13 | CanonMF4720-CW |
| 08:00:23:A5:DF:E0 | 192.168.1.9 | PanasonicNS300 |
| 70:B0:8C:82:D3:FD | 192.168.1.10 | TelephoneRecord |
| B4:A3:82:B9:51:53 | 192.168.30.2 | HK-Cam-Record |
| 9C:32:CE:22:46:13 | 192.168.1.100 | Canon-G3800-JYS |
| 28:C2:DD:72:D6:3C | 192.168.1.64 | CanonMF4720w-LD |
| 50:9A:4C:79:C5:69 | 192.168.1.8 | Dell-R230-iDRAC |
| 9C:32:CE:22:45:D7 | 192.168.1.59 | Canon-G3800-JWC |

## 地址转换->虚拟服务器设置

| 服务名称 | 外部端口 | 内部端口 | 内部服务器IP |
| :--: | :--: | :--: | :--: |
| WEB | 10000-10000 | 10000-10000 | 192.168.1.5 |
