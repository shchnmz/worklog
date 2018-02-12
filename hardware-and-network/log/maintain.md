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
| 2018/01/15 | 中山公园校区电话拨不进 | 程控交换机故障 | 更换新的松下程控交换机并重新设置分机号码 | [Panasonic（松下）电话程控交换机操作](https://github.com/northbright/Notes/blob/master/hardware/panasonic-kx-ns300-bpx-basis.md) |
| 2018/02/06 - 2018/02/12 | 威宁校区1台HP Z228不能启动 | 金士顿DDR3 1600 8GB内存条故障 | JD申请售后/换新 | 蜂鸣5次表示内存错误，金士顿终身保修，换新 |
