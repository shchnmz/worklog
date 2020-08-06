# 中山公园校区 UNBT Unifi Controller的设置

## Unifi Controller安装位置
* 联想E480笔记本上
  * Site: 中山公园校区

## 账号
* 用户: admin
* 密码: U开头密码

## WLAN Group and WiFi Networks

* "Default" Group

   | SSID | VLAN | 用途 | 密码 |
   | :--: | :--: | :--: | :--: |
   | chnmz | 20 | 无线设备，电视机/盒子 | M开头2结尾的普通WiFi密码 |
   | chnmz-printer | 10 | 打印机，和电脑同一VLAN，便于安装网络打印机 | M开头2结尾的普通WiFi密码 + `printer` |

* "chnmz-wuye" Group

   | SSID | VLAN | 用途 |
   | :--: | :--: | :--: |
   | chnmz-wuye | 22 | 提供给物业使用，连接无线设备，电视机。UAP AC Lite的MAC: 74:83:c2:36:26:6f |

## Devices

| 型号 | 位置 | MAC | WLAN Group | 2.4G Channel | 5G Channel |
| :--: | :--: | :--: | :--: | :--: | :--: |
| AC Lite | 201 | 74:83:c2:36:23:3a | default | 1 | 149 |
| AC Lite | 202 | 74:83:c2:36:21:37 | default | 6 | 153 |
| AC Lite | 203 | 74:83:c2:36:21:97 | default | 11 | 161 |
| AC Lite | 204 | 74:83:c2:36:25:e7 | default | 1 | 149 |
| AC Lite | 205 | 74:83:c2:36:28:bf | default | 6 | 153 |
| AC Lite | 206 | 78:8a:20:70:22:68 | default | 11 | 161 |
| AC Lite | 207 | 74:83:c2:36:25:71 | default | 1 | 149 |
| AC Lite | 208 | 74:83:c2:36:26:43 | default | 6 | 153 |
| AC Lite | 209 | 74:83:c2:36:26:a6 | default | 11 | 161 |
| AC Lite | 210 | 74:83:c2:36:27:c0 | default | 1 | 149 |
| AC Lite | 212 | 74:83:c2:36:16:c9 | default | 6 | 153 |
| AC Lite | 213 | 74:83:c2:36:26:f8 | default | 11 | 161 |
| AC Lite | 301 | 74:83:c2:33:91:e0 | default | 6 | 153 |
| AC Lite | 302 | 74:83:c2:36:28:ef | default | 11 | 161 |
| AC Lite | 303 | 74:83:c2:36:25:92 | default | 1 | 149 |
| AC Lite | 304 | 74:83:c2:36:21:53 | default | 6 | 153 |
| AC Lite | 305 | 74:83:c2:36:26:2a | default | 11 | 161 |
| AC Lite | 306 | 74:83:c2:36:16:ca | default | 1 | 149 |
| AC Lite | 307 | 74:83:c2:36:26:4c | default | 6 | 153 |
| AC Lite | 308 | 74:83:c2:36:28:5d | default | 11 | 161 |
| AC Lite | 309 | 74:83:c2:36:26:36 | default | 1 | 149 |
| AC Lite | 310 | 74:83:c2:33:92:24 | default | 6 | 153 |
| AC Lite | 312 | 74:83:c2:36:26:3e | default | 11 | 161 |
| AC Lite | 313 | 74:83:c2:36:28:02 | default | 1 | 149 |
| AC Lite | 2F小卖部 | 18:e8:29:e6:52:5a | default | 1 | 149 |
| AC Lite | 2F报名处 | 18:e8:29:e6:52:f3 | default | 6 | 153 |
| AC Lite | 2F素描年段办公室 | 78:8a:20:48:3f:98 | default | 11  | 161 |
| AC Lite | 2F财务室 | f0:9f:c2:d6:57:33 | default | 6 | 153 |
| AC Lite | 2F会议室 | f0:9f:c2:7c:42:8b | default | 1 | 149 |
| AC Pro | 3F理事长办公室 | fc:ec:da:f0:84:24 | default | 11 | 161 |
| AC Pro | 3F基础年段办公室 | 78:8a:20:2c:0a:2d | default | 11 | 161 |
| AC Lite | 3F校长办公室 | 78:8a:20:48:3e:90 | default | 6 | 153 |
| AC Pro | 3F幼儿年段办公室 | 78:8a:20:2c:0a:f3 | default | 1 | 149 |
| AC Lite | 3F道具室（VIP） | 18:e8:29:93:b0:94 | default | 11 | 161 |
| AC Lite | 物业 | 74:83:c2:36:26:6f | chnmz-wuye | 1 | 149 |

* 所有UAP的Transmit Power均设置为"Low"
