# 维护日志

| 日期 | 故障 | 原因 | 处理 | 备注 |
| ---- | ---- | ---- | ---- | ---- |
| 2016/10/12 | HP Z228 关机后所有风扇全速运行 | 电源故障 | HP更换新电源 | |
| 2017/05/02 | HP z238 CPU风扇有噪音 | CPU散热器和风扇固定不牢 | HP更换CPU散热器和风扇 | |
| 2017/05/06 | 勒索病毒WannaCrypt爆发，打补丁预防 | Windows Enternal Blue漏洞 | 所有电脑Windows Update至最新，Windows XP单独安装补丁 | [Customer Guidance for WannaCrypt attacks](https://blogs.technet.microsoft.com/msrc/2017/05/12/customer-guidance-for-wannacrypt-attacks/) |
| 2017/06/08 | 威宁校区明日系统主机报CPU风扇故障 | CPU散热器损坏 | 更换CPU散热器和风扇 | 老775平台,换红海mini |
| 2017/07/01 | 中山校区多台电脑不能上网 | 错误插入路由模式TP-Link路由器的WAN口，DHCP冲突 | 插入LAN口，关闭DHCP | 中山3楼会议室作为幼儿段办公室，缺少网口 |
| 2017/07/07 | UAP AC Lite工作3天后突然不工作 | TP-Link SG1005P 交换机POE供电与UAP AC Lite兼容性不好 | 更换原装电源正常工作 |  |
| 2017/07/28 | TP-Link TL-WN725无线网卡安装后蓝屏 | 驱动精灵的驱动有问题 | 官网下载驱动 |  |
| 2017/07/28 | Ralink PCI-E 300M 无线网卡 Win7连接显示无Internet连接 | Win7自带802.11n驱动有问题 | 使用驱动精灵重新安装无线网卡驱动 |  |
| 2017/07/28 | 同时使用DP转VGA适配器与Ralink PCI-E 无线网卡(有天线)造成黑屏 | 天线有无线干扰，DP转VGA线无屏蔽 | 更换另外品牌DP转VGA适配器(绿联) | [DP转VGA适配器会因为无线网卡天线造成的干扰而不工作](https://github.com/northbright/Notes/blob/master/hardware/dp-to-vga-adapter-will-not-work-because-of-emi-of-wireless-antenna.md) |
| 2017/08/10 | AMP网络面板的螺丝与中国86盒不兼容 | 螺丝较细 | 另行购买螺丝 | |
| 2017/08/10 | H3C 1224vr2 交换机故障。上电后所有指示灯亮，不通。 | 设备故障 | 换货 |  |
| 2017/10/20 | HP Z238不能启动。按下电源键电源灯亮，放开后灭，不能启动。 | CMOS有问题 | 清除CMOS，然后启动 | [HP Z238 Failed to Power On](https://github.com/northbright/Notes/blob/master/hardware/hp-z238-failed-to-power-on.md)
| 2018/01/15 | 中山公园校区电话拨不进 | 程控交换机故障 | 更换新的松下程控交换机并重新设置分机号码 | [Panasonic（松下）电话程控交换机操作](https://github.com/northbright/Notes/blob/master/hardware/panasonic-kx-ns300-basis.md) |
| 2018/02/05 | 威宁校区1台HP Z238工作站和DELL P2417显示器显示故障 | 显示器自带DP线故障 | 新购绿联带卡扣的DP线更换 |
| 2018/02/06 - 2018/02/12 | 威宁校区1台HP Z228不能启动 | 金士顿DDR3 1600 8GB内存条故障 | JD申请售后/换新 | 蜂鸣5次表示内存错误，金士顿终身保修，换新 |
| 2018/12/08 - 2018/02/12 | 多台EPSON针式打印机不能工作 | Windows Update更新导致故障 | 在微软没有发布新的更新前：卸载导致问题的更新；后续直接安装新的更新 | [Unable Print to EPSON Dot Matrix Printer](https://github.com/northbright/Notes/blob/master/hardware/unable-to-print-epson-dot-matrix-printers-on-windows.md) |
| 2018/02/20 - 2018/02/23 | 中山公园校区网络无Internet连接 | 网络中存在一个TP-LINK WR740N路由器, DHCP服务器开启。春节假期工作电脑关闭7天，启动后得到该路由器分配的192.168.0.x的IP | 在中山公园物业值班室找到路由器, 关闭DHCP，将WAN口封好 | 物业在中山公园校区装修好时，私自将学校网线接入物业值班室 |
| 2018/02/23 | 中山公园校区1路电话无法拨入／拨出 | 电信光猫直接接电话机也无信号，光猫可能有问题 | 重启光猫 | 之前也碰到过类似问题 |
| 2018/02/24 | 古北校区电信宽带断网重连3次 | H3C ER5200G2的log显示电信端无信号返回导致断线重拨 | 保修10000，上门检测发现ping值有时很高，刷新电信后台数据，重新测试一段时间，如果还有问题换光猫 | 光信号值良好 |
| 2018/02/24 | 威宁校区报名处第1台EPSON针式打印机不工作 | 该打印机原来是USB连接至第2台电脑，并设置打印机共享给第1台，现在发现该打印机共享取消了 | 重新共享打印机 | 第2台电脑之前因为Windows Update造成EPSON针式打印机不工作, 见[Unable Print to EPSON Dot Matrix Printer](https://github.com/northbright/Notes/blob/master/hardware/unable-to-print-epson-dot-matrix-printers-on-windows.md) |
| 2018/03/06 | 中山公园校区1门外线拨入，数字总机接起后，另外1门外线拨入没有响铃，造成没有人接听 | 2门外线均接入到松下ns300电话交换机后，数字总机没有设置忙转 | 配套松下数字电话机2根外线设置忙转 | [Panasonic（松下）电话程控交换机操作](https://github.com/northbright/Notes/blob/master/hardware/panasonic-kx-ns300-basis.md) |
| 2018/04/03 | 上午明日系统不能访问 | 服务器（明日系统运行在虚拟机中）被意外断电然后再上电 | 开启虚拟机运行明日系统，开启自动备份的[navicat-backup](https://github.com/northbright/navicat-backup)的server | 2018/04/02晚上19:00装修施工断电 |
| 2018/04/17 | 1台Win10的电脑上已安装的佳能打印机消失，且卸载／重新安装打印机驱动均失败 | Printer Spooler服务停止，启动失败:没有足够资源错误 | 运行netsh winsock reset | [Failed to Start Printer Spooler Service](https://github.com/northbright/Notes/blob/master/Windows/printer/failed-to-start-printer-spooler-service.md) |
| 2018/04/26 | 明日系统不能访问 | 机柜电源所在电路跳电 | 物业电工临时接电线 | 装修时电路存在问题，准备维修。因机柜／机房空间实在太小，根本没有安装UPS的可能 |
| 2018/04/27 | 1台Dell P2317H显示器上电不能点亮 | 硬件故障 | JD售后让直接联系Dell售后: 4008811852(手机拨打) | 显示器需拍3张照片: 1. 正面（拍到边框) 2.反面（拍到边框） 3. Service Tag/序列号 |
| 2018/04/27 | 1台Dell主机因为学校跳电，非正常关机后不能启动: 引导信息有错误 | MBR损坏 | 使用WePE进入系统，使用DiskGenius重建MBR | [Boot Manager: Windows Failed to Start with Status: 0xc000000f](https://github.com/northbright/Notes/blob/master/Windows/boot/boot-manager-windows-failed-to-start-with-status-0xc000000f.md) |
| 2018/05/23 | 海康威视录象机萤石云连不上，显示"不在线" | 没有输入验证码 | 输入6个任意大写字母（A/B/C/D/E/F除外）| [HikVision Camera Recorder Can Not Connect to 萤石云(ezviz)](https://github.com/northbright/Notes/blob/master/hardware/hikvision-camera-recorder-can-not-connect-to-ying-shi-yun.md) | 
