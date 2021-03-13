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
| 2017/07/28 | 同时使用DP转VGA适配器与Ralink PCI-E 无线网卡(有天线)造成黑屏 | 天线有无线干扰，DP转VGA线无屏蔽 | 更换另外品牌DP转VGA适配器(绿联) | [DP转VGA适配器会因为无线网卡天线造成的干扰而不工作](https://github.com/northbright/Notes/blob/master/hardware/pc/dp-to-vga-adapter-will-not-work-because-of-emi-of-wireless-antenna.md) |
| 2017/08/10 | AMP网络面板的螺丝与中国86盒不兼容 | 螺丝较细 | 另行购买螺丝 | |
| 2017/08/10 | H3C 1224vr2 交换机故障。上电后所有指示灯亮，不通。 | 设备故障 | 换货 |  |
| 2017/10/20 | HP Z238不能启动。按下电源键电源灯亮，放开后灭，不能启动。 | CMOS有问题 | 清除CMOS，然后启动 | [HP Z238 Failed to Power On](https://github.com/northbright/Notes/blob/master/hardware/hp/hp-z238-failed-to-power-on.md)
| 2018/01/15 | 中山公园校区电话拨不进 | 程控交换机故障 | 更换新的松下程控交换机并重新设置分机号码 | [Panasonic（松下）电话程控交换机操作](https://github.com/northbright/Notes/blob/master/hardware/panasonic/panasonic-kx-ns300-basis/panasonic-kx-ns300-basis.md) |
| 2018/02/05 | 威宁校区1台HP Z238工作站和DELL P2417显示器显示故障 | 显示器自带DP线故障 | 新购绿联带卡扣的DP线更换 |
| 2018/02/06 - 2018/02/12 | 威宁校区1台HP Z228不能启动 | 金士顿DDR3 1600 8GB内存条故障 | JD申请售后/换新 | 蜂鸣5次表示内存错误，金士顿终身保修，换新 |
| 2018/12/08 - 2018/02/12 | 多台EPSON针式打印机不能工作 | Windows Update更新导致故障 | 在微软没有发布新的更新前：卸载导致问题的更新；后续直接安装新的更新 | [Unable Print to EPSON Dot Matrix Printer](https://github.com/northbright/Notes/blob/master/hardware/epson/unable-to-print-epson-dot-matrix-printers-on-windows.md) |
| 2018/02/20 - 2018/02/23 | 中山公园校区网络无Internet连接 | 网络中存在一个TP-LINK WR740N路由器, DHCP服务器开启。春节假期工作电脑关闭7天，启动后得到该路由器分配的192.168.0.x的IP | 在中山公园物业值班室找到路由器, 关闭DHCP，将WAN口封好 | 物业在中山公园校区装修好时，私自将学校网线接入物业值班室 |
| 2018/02/23 | 中山公园校区1路电话无法拨入／拨出 | 电信光猫直接接电话机也无信号，光猫可能有问题 | 重启光猫 | 之前也碰到过类似问题 |
| 2018/02/24 | 古北校区电信宽带断网重连3次 | H3C ER5200G2的log显示电信端无信号返回导致断线重拨 | 保修10000，上门检测发现ping值有时很高，刷新电信后台数据，重新测试一段时间，如果还有问题换光猫 | 光信号值良好，更新：发现是因为电信网关Raisecom MSG2200-T4的Known issue。[H3C ER3260 Router Will Lose Connection and Reconnect(PPPOE) when ISP Bandwidth is Larger than 100m](https://github.com/northbright/Notes/blob/master/hardware/h3c/h3c-er-3260-router-will-lose-connection-and-reconnect-when-isp-bandwidth-is-larger-than-100m.md) |
| 2018/02/24 | 威宁校区报名处第1台EPSON针式打印机不工作 | 该打印机原来是USB连接至第2台电脑，并设置打印机共享给第1台，现在发现该打印机共享取消了 | 重新共享打印机 | 第2台电脑之前因为Windows Update造成EPSON针式打印机不工作, 见[Unable Print to EPSON Dot Matrix Printer](https://github.com/northbright/Notes/blob/master/hardware/epson/unable-to-print-epson-dot-matrix-printers-on-windows.md) |
| 2018/03/06 | 中山公园校区1门外线拨入，数字总机接起后，另外1门外线拨入没有响铃，造成没有人接听 | 2门外线均接入到松下ns300电话交换机后，数字总机没有设置忙转 | 配套松下数字电话机2根外线设置忙转 | [Panasonic（松下）电话程控交换机操作](https://github.com/northbright/Notes/blob/master/hardware/panasonic/panasonic-kx-ns300-basis/panasonic-kx-ns300-basis.md) |
| 2018/04/03 | 上午明日系统不能访问 | 服务器（明日系统运行在虚拟机中）被意外断电然后再上电 | 开启虚拟机运行明日系统，开启自动备份的[navicat-backup](https://github.com/northbright/navicat-backup)的server | 2018/04/02晚上19:00装修施工断电 |
| 2018/04/17 | 1台Win10的电脑上已安装的佳能打印机消失，且卸载／重新安装打印机驱动均失败 | Printer Spooler服务停止，启动失败:没有足够资源错误 | 运行netsh winsock reset | [Failed to Start Printer Spooler Service](https://github.com/northbright/Notes/blob/master/Windows/printer/failed-to-start-printer-spooler-service.md) |
| 2018/04/26 | 明日系统不能访问 | 机柜电源所在电路跳电 | 物业电工临时接电线 | 装修时电路存在问题，准备维修。因机柜／机房空间实在太小，根本没有安装UPS的可能 |
| 2018/04/27 | 1台Dell P2317H显示器上电不能点亮 | 硬件故障 | JD售后让直接联系Dell售后: 4008811852(手机拨打) | 显示器需拍3张照片: 1. 正面（拍到边框) 2.反面（拍到边框） 3. Service Tag/序列号 |
| 2018/04/27 | 1台Dell主机因为学校跳电，非正常关机后不能启动: 引导信息有错误 | MBR损坏 | 使用WePE进入系统，使用DiskGenius重建MBR | [Boot Manager: Windows Failed to Start with Status: 0xc000000f](https://github.com/northbright/Notes/blob/master/Windows/boot/boot-manager-windows-failed-to-start-with-status-0xc000000f.md) |
| 2018/05/23 | 海康威视录象机萤石云连不上，显示"不在线" | 没有输入验证码 | 输入6个任意大写字母（A/B/C/D/E/F除外）| [HikVision Camera Recorder Can Not Connect to 萤石云(ezviz)](https://github.com/northbright/Notes/blob/master/hardware/hikvision/hikvision-camera-recorder-can-not-connect-to-ying-shi-yun.md) | 
| 2018/08/17 | 中山公园教室电脑不能开机 | 电源损坏 | 购买航嘉Jumper450B电源替换 | 2台 |
| 2018/08/17 | 中山公园共享打印机不能访问 | 服务器意外断电，共享打印机失效 | 重新安装打印机驱动 | "打印机属性"->"高级"->"在后台处理完最后一页时开始打印" |
| 2018/08/22 | 明日系统不能访问 | 8月22日 01:40分楼内电路跳电,交换机以及服务器均重启,MySQL损坏 | 重建虚拟机,导入数据备份 | MySQL损坏不能连接数据库可以直接回复VirtualBox的Snapshot,然后恢复数据 |
| 2018/11/26 | 威宁校区网络突然变慢 | 电信的网关Raisecom MSG2200-T4出现大量UDP组播占用incoming带宽 | 要求电信更换光猫（单口） | 之前古北校区出现断网也是因为Raisecom MSG2200-T4的known issue，[Shanghai Telecom FTTH(commercial) Becomes Very Slow](https://github.com/northbright/Notes/blob/master/hardware/telecom/shanghai-telecom-ftth-becomes-very-slow/shanghai-telecom-ftth-becomes-very-slow.md) |
| 2018/12/24 | 明日系统出现License到期错误，但是购买的是永久授权 | 确认是2018/12/24到期 | 联系第三方软件服务商修复 | [Get License Information of ming800](https://github.com/northbright/Notes/blob/master/Software/ming/get-license-information-of-ming.md) |
| 2019/02/19 - 2019/02/21 | 中山公园幼儿年段，一台HP Z228不能启动 | WD的1T硬盘出现坏道，05,C4,C5故障 | 替换一块硬盘 | 重新安装系统，连接共享文件夹，共享打印机 |
| 2019/02/19 - 2019/02/21 | 中山公园领导办公室，一台监控用的HP Z238间歇性蓝屏（CLOCK WATCHDOG TIMEOUT） | 之前已经更换过主板，该蓝屏代码可能是CPU故障 | 联系HP售后，更换CPU和主板 | 更换后连续4天一直在IE远程监控，未出现蓝屏 |
| 2019/03/13 | 中山公园1台HP Z238工作站不能开机，电源按下灯亮，放开灯灭 | CMOS/BIOS故障 | 按下主板上黄色按钮，恢复出厂BIOS设置 | |
| 2019/03/13 | 中山公园1台HP Z228工作站不能上网 | 安装了VPN软件 | 在网络的连接选项中，取消代理服务器的设置，卸载VPN软件 | |
| 2019/04/09 | 威宁1台HP Z238工作站不能上网 | 安装了VPN软件 | 在网络的连接选项中，取消代理服务器的设置，卸载VPN软件 | |
| 2019/04/15 | 威宁校区1根电信宽带不能上网，PPPOE拨号始终失败，网关有红色灯 | 电信线路问题 | 保修电信维修 | 天山路水城路的电信的光纤节点有问题，后修复 |
| 2019/04/19 | 威宁校区共享服务器不能远程桌面 | 网络位置突然变成"公共"，防火墙没有为"公共"添加远程桌面的例外 | 将网络位置设置成"工作" | [Configure Firewall Exception for Remote Desktop](https://github.com/northbright/Notes/blob/master/Windows/remote-desktop/configure-firewall-exception-for-remote-desktop.md) |
| 2019/04/24 | 中山公园校区的电脑不能上网，网络显示黄色感叹号 | 04/23晚上物业停电维修，2F的小卖部有一台TP-Link WR740路由器新接入，DHCP没有被禁用 | 禁用DHCP服务器 | 中山公园校区停电维修比较频繁，如果网络有接入路由器且DHCP没被禁用，供电恢复后，电脑的IP都很可能将由新接入的路由器分配，而不是H3C的企业路由器 |
| 2019/04/24 | 中山公园校区的数字总机不响铃 | 松下数字电话机被设置静音 | 调整音量 | [Digital Phone of Panasonic NS 300 was Muted](https://github.com/northbright/Notes/blob/master/hardware/panasonic/digital-phone-of-panasonic-kx-ns300-was-muted.md) |
| 2019/05/05 | 中山公园校区报名处共享打印机（发票针打）不能访问 | 安装了金山毒霸，系统防火墙被禁用 | 卸载金山毒霸，修复防火墙，配置规则 | [Shared Folders / Printers can not be Accessed by Other PCs Due to Duba has been Installed on Windows 7](https://github.com/northbright/Notes/blob/master/Windows/printer/shared-folders-and-printers-can-not-be-accessed-by-other-pcs-due-to-duba-has-been-installed-on-windows-7.md)  |
| 2019/05/05 | 中山公园校区报名处的主任处的网络面板脱落 | 扯动造成脱落 | 网络工程公司帮忙更换网络/电话模块 | 原ping同网段电脑164，修复后64，装修使用五类线 | 
| 2019/07/02 | 9号教室在海康威视的网络界面不能预览 | 摄像头的子码流设置有问题 | 按照其他正常摄像头来设置子码流 | [Failed to Preview One Channel of HikVision Recorder](https://github.com/northbright/Notes/blob/master/hardware/hikvision/failed-to-preview-on-channel-of-hikvision-recorder.md) |
| 2019/07/02 | 中山公园校区1路外线电话不能拨入和拨出 | 电信的Modem直接连接电话机也是不能拨入拨出，出现故障 | 重启电信Modem | 没有开启制冷空调，温度较高，需要开启 | 
| 2019/07/27 | 中山公园校区打印机不能工作 | 打印测试页提示需要更新打印机驱动 | 更新打印机驱动 | [Need Update Printer Driver to Make Printer Work Again](https://github.com/northbright/Notes/blob/master/Windows/printer/need-update-printer-driver-to-make-printer-work-again.md) |
| 2019/07/29 | 中山公园校区小卖部无线网络故障 | 网线/模块问题导致TP-LINK路由器不能获取IP | 更换ASUS NT-R56U，更换网线 | 使用的软跳线可能有质量问题，且第一次装修的网线模块可能又问题 |
| 2019/07/30 | 中山公园校区报名处电脑不能上网 | 从交换机直接接跳线，ping网关3秒，报名处新更换的NT-R56U的IP不能访问，SSID的密码提示不对，但把路由器接入到其他办公室的面板，能找到IP，密码又对了 | 报名处的网口暂时移除设备，同时更换机房的备用交换机 | 报名处的网口对应的管中的网线或者模块有故障 |
| 2019/07/27 | 金沙江校区的海康威视录像机通过网络看预览提示错误码流加密 | 萤石云的密码和本地码流密码不一致，设置一致后，需要按“保存” | 重新设置码流密码，保存 | [海康威视监控录像机因为码流密钥不正确导致不能预览](https://github.com/northbright/Notes/blob/master/hardware/hikvision/hikvision-camera-can-not-preview-due-to-incorrect-stream-key.md) |
| 2019/08/27 | 威宁校区所有电话分机出现滋滋噪音 | 松下程控交换机可能过热 | 远程登录后重启设备 | [Noise Appears in All Phones of Panasonic kx ns300](https://github.com/northbright/Notes/blob/master/hardware/panasonic/noise-appears-in-all-phones-of-panasonic-kx-ns300.md) |
| 2019/08/28 | 威宁校区的海康威视在Web Admin以及萤石云不能实时预览 | 散热条件差可能造成设备长时间运行过热 | 重启设备 | 在本地可以正常预览以及回放。[Hikvision Recorder Can Not Preview on Web Admin or Yingshiyun](https://github.com/northbright/Notes/blob/master/hardware/hikvision/hikvision-recorder-can-not-preview-on-web-admin-or-yingshiyun.md) |
| 2019/08/30 | 威宁校区松下数字电话接入第1路电话后，第2路电话进入只有闪灯 | 重启松下电话交换机后，数字总机忙转到分机的设置丢失 | 重新设置数字总机忙转 | [Panasonic（松下）NS300电话程控交换机操作](https://github.com/northbright/Notes/blob/master/hardware/panasonic/panasonic-kx-ns300-basis/panasonic-kx-ns300-basis.md) |
| 2020/05/11 | 金沙江校区28号教室一台HP Z238工作站总是掉电 | 主板故障 | 更换主板 | [HP Z238 Powered Off Automatically](https://github.com/northbright/Notes/blob/master/hardware/hp/hp-z238-powered-off-automatically.md) |
| 2020/05/14 | 金沙江校区11号教室的网口不通 | 2号机房的配线架连交换机的跳线插头松动（交换机端）| 重新插紧条线 | |
| 2020/05/14 | 中山公园查询上海电信宽带上行只有20M | 升级下行500M/上行100M的时候，电信后台数据可能没有更新 | 打电话给电信经理，后台数据更新。然后让电信师傅上门测试速度 | 测试速度下行500M/上行100M |
| 2020/05/18 | 中山公园校区老的海康威视监控录像机不能连接萤石云 | 有的时候”在线“，有时”不在线“，提示解析域名失败。DNS配置为10.0.100.2。另外一台新的海康威视录像机同样DNS设置，连接萤石云正常。 | 暂时这样，等待大修的机会，连之前的录像机一起更换掉。| |
| 2020/05/18 | 威宁校区3号/8号教室的网络面板松动 | 因之前其他施工暴力装修损坏 | 请网络公司修复 | |
| 2020/05/18 | 金沙江校区的3号，4号教室的摄像头不工作 | 连续工作6个月死机了 | 重新上电重启 | [Hikvision Camera Did Not Work After Running 6 Months](https://github.com/northbright/Notes/blob/master/hardware/hikvision/hikvision-camera-did-not-work-after-running-for-6-months.md) |
| 2020/05/19 | 古北校区2楼教室办公室的电脑有时断网 | 之前使用老的面板：进门左侧第一个双口面板，左面的网口单独连接第一台电脑，一直没问题。右面的网口，连接一个H3C Mini 16口的交换机。断网的就是这个交换机上的电脑。| 将双口面板的左面的网口连接一台新的水星8口交换机，第一台电脑和其他电脑都连接在新交换机上。| |
| 2020/05/27-2020/05/28 | 中山公园校区，理事长办公室HP Z238工作站启动蓝屏 | 代码：0x00000124，让HP维修站员工上门，确认CPU故障 | 更换其他Z238电脑的CPU，走后续维修流程 | 2019/07，Z238已经过保 |
| 2020/06/24 - 2020/07/17 | 威宁校区电话录音盒不能通过IP访问 | 故障 | 返厂维修 | 之前4月装修，机柜可能有过断电 |
| 2020/10/14 | 威宁校区一个宽带拨号连不上 | 中兴的猫 LOS 红灯 | 保修 | 地下室机房电信机柜的接口可能松动 |
| 2020/11/03 | 中山公园校区5个教室摄像头损坏 | 故障 | 更换新的摄像头 |  |
| 2020/11/03 | 中山公园校区理事长办公室的KVM切换器不工作 | 电源损坏 | 更换新的电源 | 连接二楼机房 |
| 2020/11/15 | 威宁校区座机接电话，听不到对方声音。同时来电显示消失 | 11/14日注销了电话套餐绑定的4G手机卡。拨打10000号提示单位没有实名认证 | 重启Panasonic电话交换机，听不到声音的问题解决 | 座机实名认证等待电信回复 |
| 2020/12/09 - 2020/12/10 | 威宁校区WAN 2宽带拨号掉线 | 原ZTE光猫故障 | 更换新的ZTE光猫，LAN口1连接交换机 |  |
| 2021/01/02 | 金沙江校区大办公室更换之前摔坏的显示器 | 教师不小心摔坏一台Dell P2719 显示器 | 新购一台 | 备注 |
| 2021/01/02 | 金沙江报名处电脑运行缓慢 | HP Z228 i5, 8G, 2T, HDD, Win10，机械硬盘同时处理图形软件比较慢 | 更换清华同方 i7 8700, 128 SSD, 1T HDD, 1050Ti | 做设计用 |
| 2021/01/13 | 中山公园校区前台第一个电话分机没有声音 | 在新办公室布线时去机房，可能碰松了110配线架上的配线 | 重新打紧配线 |  |
| 2021/01/13 | 威宁校区第一件办公室打印机打印非常缓慢 | 打印机对应网口的模块测试，机柜对应的跳线故障 | 更换机柜的跳线，更换模块重新接线 | |
| 2021/01/15 | 威宁校区教研室的EPSON L6168提示更换维护箱，不能打印 | 维护箱芯片计数满（清洗/深度清洗/开关机会计数） | 更换T04D1维护箱（废墨垫）  | [EPSON 打印机驱动提示“服务请求，打印机的部件到使用期限”](https://github.com/northbright/Notes/blob/master/hardware/epson/printer-driver-says-a-part-inside-your-printer-is-at-the-end-of-its-service-life.md) |
| 2021/02/04 | 古北校区有一台电脑，耳机插入没有声音 | 音频设备有2个，NVIDIA以及REALTEK，选择了NVIDIA的设备 | 重新选择 REALTEK 解决  |  |
| 2021/02/16 | 威宁校区一台NZXT机箱的电脑，不能开机 | 机箱电源按钮连接主板的PWR SW的针脚的连线可能故障 | 使用 RESET 按钮替换（连接 PWR SW）| [Cable Connected Power Button and Mainboard Does NOT Work Cause PC Can NOT Boot](https://github.com/northbright/Notes/blob/master/hardware/pc/cable-connected-power-button-and-mainboard-does-not-work-cause-pc-can-not-boot.md) |
| 2021/03/02 | 威宁校区Unifi Controller发现有1个AP掉线，原本10个，只发现9个，“走廊从最西面数第1个”掉线 | 经过拆下来查看，网口处积水断路造成故障 | 准备采购新的替换 | 可能夏天走廊热空气与上方消防水管管壁形成冷凝水，下次安装位置需要避开水管 |
| 2021/03/03 - 2021/03/09 | iPhone 屏幕镜像，找不到同一网络中的小米电视和小米盒子 | UNBT的Unifi Controller中的无线网络，2.4G和5G共享一个SSID，开启了5G优先 | 2.4G和5G独立为2个不同的 SSID | [Can Not Find Airplay Devices under One Dual Band SSID of Unifi Controller](https://github.com/northbright/Notes/blob/master/hardware/ubnt/can-not-found-airplay-devices-under-one-dual-band-ssid-of-unifi-controller.md)  | 
| 2021/03/03 - 2021/03/09 | 威宁，中山公园，金沙江校区，小米盒子，小米电视在投屏镜像的显示的设备名称混乱 | 没有统一命名 | 设备名为教室号，安装乐播投屏App，乐播投屏的设备名称为：乐播投屏 + 教室号 | | 
| 2021/03/09 | 金沙江校区2号教室的摄像头通道丢失，不能预览和回放 | 摄像头死机 | 摄像头处的网线，重新做了水晶头，后续如果还死机，需要返厂维修 | | 
| 2021/03/09 | 金沙江校区，不知道 UBNT Unifi Controller 中的 AP 的位置 | 需要在 UNBT Unifi Controller 中，将 AP 的 Alias 和物理位置对应 | 使用 Locate 定位设备，然后修改 AP 的Alias | |
| 2021/03/12 | 威宁玻璃房办公室3台电脑同时出现打印的图片当中出现空白区域 | Windows 10的 KB5000808 更新导致打印时蓝屏，出现空白区域 | 建议等待最新 Windows 10的更新，或者卸载 KB5000802，KB5000808 | [There is a Blank Area in the Middle of Printed Image after KB5000808 Installed Automatically on Windows 10](https://github.com/northbright/Notes/blob/master/Windows/printer/there-is-a-blank-area-in-the-middle-of-printed-image-after-kb5000808-installed-automatically-on-windows-10.md) |
