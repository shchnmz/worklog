# 工作日志

| 日期 | 事项 | 备注 |
| ---- | ---- | ---- | 
| 2017/08/10 | 古北校区网络AMP端接工具与安装人员沟通 | AMP模块，AMP SL配线架与1725150-1工具如何使用 |
| 2017/08/10 | 古北校区无线AP设置 | 1. Unifi AC Lite 5个 2. Unifi Controller设置网络，添加设备 |
| 2017/08/10 | 古北校区网络路由器配置 | 1. 电信网关在线设置成桥接模式. 2. H3C E5200G2创建VLAN 3(192.168.3.1). 3. VLAN 3 DHCP池: 192.168.3.70 - 192.168.3.254用于海康威视录像机(192.168.1.70)以及摄像头. [参考文档](https://github.com/northbright/Notes/blob/master/h3c/hardware/vlan-settings-for-h3c-router-and-ubnt-uap.md)|
| 2017/08/10 | 古北校区海康威视PC端软件调试 | 1. 海康威视监控PC端安装, PC需要和录像机在同一网段. 2. 在设备中选中录像机，添加设备。3. 画面选择25格. |
| 2017/08/13 | 古北校区海康威视手机App调试 | 1. iOS App Store下载萤石App 2. 在录像机的网络设置中找到二维码，打开App扫码添加设备 |
| 2017/08/13 | 古北校区17台工作站内存添加，软件安装 | 1. 10台z240, 7台z238，内存均添加至8G. 2. 必要软件安装 |
| 2017/08/25 | Canon 2204N打印机驱动安装 | WiFi连接，设置静态IP |
| 2017/08/25 | Canon PIXMA G3800打印机设置 | [佳能PIXMA G3800打印机WLAN设置](https://github.com/northbright/Notes/blob/master/Software/driver/canon/wlan-configuration-of-canon-pixma-g3800-printer/wlan-configuration-of-canon-pixma-g3800-printer.md) |
| 2017/08/28 | UBNT UAP AC Lite设置为静态IP | [可以忽略UBNT UAP的网络设置中使用静态IP后提示的IP冲突警告](https://github.com/northbright/Notes/blob/master/hardware/ubnt/ignore-the-ip-conflict-warning-when-use-static-ip-for-ubnt-uap.md) |
| 2017/09/27 | 财务室安装Canon MF4720w打印机 | WiFi连接，设置静态IP |
| 2018/01/04 - 2018/01/05 | 威宁校区改造，教务处临时搬迁至6，7号教室。每个教室10台PC组装接线。新增2根网线从机柜至6，7号教室，多级交换机级连组成临时网络。网络打印机连接。 | 临时使用约40天 |
| 2018/01/15 | 中山公园校区配合机房安装松下程控交换机 | [中山公园校区电话设置(2018/01/15)](https://github.com/shchnmz/worklog/blob/master/hardware-and-network/doc/zhongshan-park/telephone-settings-of-zhongshan-park-campus.md), [Panasonic（松下）电话程控交换机操作](https://github.com/northbright/Notes/blob/master/hardware/panasonic/panasonic-kx-ns300-basis/panasonic-kx-ns300-basis.md) |
| 2018/01/15 - 2018/02/06 | 配合第三方公司进行威宁校区网络重新布线，摄像头更换为高清，电话重新布线，更换电话交换机以及录音盒 | 机柜位置移动，所有线重新连接 |
| 2018/01/20 | 威宁校区财务室新装2台HP Z238工作站 | |
| 2018/01/24 | 威宁校区上海电信宽带光纤接入点移动到新机柜 | 老光纤1根，新增1根 |
| 2018/02/05 | 威宁校区/中山公园校区电话程控交换机重新配置：另外一门直线接入总机 | 2门外线都接到数字总机，分机都可以抢接 |
| 2018/02/06 | 威宁校区海康威视监控录像机查看监控以及回放调试 | [海康威视录像机基本操作](https://github.com/northbright/Notes/blob/master/hardware/hikvision/hikvision-recorder-basis/hikvision-recorder-basis.md) |
| 2018/02/09 | 中山公园校区安装8台HP Z228工作站。设置打印机，共享服务器 | 新增8位教师 2F:1位，3F:7位|
| 2018/02/09 | 中山公园校区使用2台UBNT UAP AC Pro和2台水星POE交换机进行新办公区域无线覆盖 | 3F的2个新办公室 |
| 2018/02/25 | 古北校区电信宽带升级200M | 电信免费升级200M，更换新网关，路由器连接LAN 7, QOS设置单IP限速上下行均20M |
| 2018/06/21 - 2018/07/05 | 中山公园校区改造，2楼和3楼的摄像头更新，211/311教室新增摄像头，306划出新办公室，新增无线AP | 机房重新布线，新增交换机和硬盘录像机 |
| 2018/07/04 | 中山公园共享服务器server1配置允许远程登录 | [Remote Desktop Authentication Error: The Function is Not Supported](https://github.com/northbright/Notes/blob/master/Windows/remote-desktop/remote-desktop-authentication-error-the-function-is-not-supported.md)  |
| 2018/07/04 | 中山公园校区Unifi Controller重新配置: chnmz网络用于手机，VLAN ID: 20,chnmz-pc用于电脑和打印机 | Unifi Controller安装在server1上, [中山公园校区网络更新设置(2018/07/04)](https://github.com/shchnmz/worklog/blob/master/hardware-and-network/doc/zhongshan-park/network-settings-of-zhongshan-park-campus.md) |
| 2018/08/28 | 和航今科技一起去古北校区，确认新增老师需要增加的网络节点 | 教务处8个，206教室1个，阁楼5个（含1个打印机） |
| 2018/09/13 | 艾特租租给威宁校区9台清华同方电脑到货。安装软件，连接共享文件夹／打印机 | |
| 2018/09/18 - 2018/09/19 | 和航今公司去中山公园校区306办公室，2楼／3楼教务处有线网络布线 | 306办公室原先只有无线网络，增加有线网络 |
| 2018/09/20 | 艾特租租给中山公园校区9台清华同方电脑到货。安装软件，连接共享文件夹／打印机 | [Win10 PC Can't Access Shared Folder by Name after 3 H3C Switches Stacked](https://github.com/northbright/Notes/blob/master/Windows/network/win10-pc-can-not-access-shared-folder-by-name-after-3-h3c-swithes-stacked.md) |
| 2018/12/20 | 中山公园校区新装8台HP Z238(Win10 Home)工作站，使用Dism++来部署已经配置的镜像(共享，打印机，软件，设置)。 | 新老师 |
| 2018/12/23 | 威宁公园校区新装10台HP Z238(Win10 Home)工作站，使用Dism++来部署已经配置的镜像(共享，打印机，软件，设置)。| 新老师 |
| 2019/01/10 | 威宁校区更换H3C ER3260路由器为新购H3C ER8300G2-X | WAN 2连接ZTE光猫。电信200M款带，升级路由器支持千兆模式 |
| 2019/02/17 | 威宁校区新购5台子母电话机，用于转班期间电话繁忙的解决方案 | 第一间办公室，教务处 |
| 2019/02/18 | 古北校区新购1台Canon G3800打印机，驱动安装到server | WiFi连接 |
| 2019/02/22 | 威宁校区报名处1台Canon MF4700打印机驱动安装到server | WiFi连接 |
| 2019/05/09 | 金沙江路校区安装电信宽带，2路电话移机 | [Setup Call Forwarding Service of Shanghai Telecom](https://github.com/northbright/Notes/blob/master/telecom/setup-call-forwarding-service-of-shanghai-telecom.md)  |
| 2019/05/05 - 2019/05/29 | 设置金沙江校区交换机，路由器，UBNT AP控制器 | [金沙江校区网络设置](https://github.com/shchnmz/worklog/blob/master/hardware-and-network/doc/jinshajiang/network-settings-of-jinshajiang-campus.md) |
| 2019/05/05 - 2019/05/29 | 设置金沙江校区监控录像机 | [金沙江校区监控摄像头设置](https://github.com/shchnmz/worklog/blob/master/hardware-and-network/doc/jinshajiang/camera-settings-of-jinshajiang-campus.md) |
| 2019/05/23 - 2019/05/25 | 金沙江校区安装16台HP Z238工作站 | 教师以及报名处使用，新增SSD |
| 2019/07/02 | 中山公园2楼会议室改成教师办公室，航今公司负责网络改造，3楼仓库改造领导绘画室接入UBNT AP | 2F监控用的电视机移动位置，航今重新把VGA线从顶上走线，连接电视机 |
| 2019/07/03 - 2019/07/03 | 中山公园安装6台HP Z238工作站 | 新教师2楼会议室 |
| 2019/07/20 | 古北校区新办公室安装3台HP Z238工作站 | 改造的新教师办公室 |
| 2019/08/22 - 2019/08/26 | 威宁/中山公园校区新采购小米盒子4，连接电视播放课件 | 连接无线网络，安装金山WPS投屏软件 |
| 2019/10/15 - 2019/11/02 | 中山公园校区网络升级 | 升级H3C核心/接入交换机，重新设置VLAN，所有教室AP覆盖 |
| 2019/11/03 | 中山公园校区重新安装打印机驱动 | 使用网络打印机的方式，不再使用共享打印机 |
| 2019/11/27 - 2019/11/29 | 古北，中山公园，威宁校区升级上海电信500M下行宽带 | 需要升级网关 |
| 2019/12/21 | 中山公园校区，UBNT AP的设置 | 为每个UAP设置2.4G / 5G的Channel。2.4G: 1/6/11, 5G: 149/153/161，所有的UAP的Transimit Power设置为Low |
| 2020/01/02 | 金沙江校区28号教室改造成教师办公室，10个工位，有线网络重新从墙壁的面板布线到工位的办公桌下 | 还少1个网口，最后1个网口是电话口 |
| 2020/03/23 | 因为威宁校区装修，明日系统数据备份到一台新的主机，搬迁至金沙江校区 | Win10 Home，设置38天暂停更新 |
| 2020/03/24 - 2020/04/30 | 威宁校区装修：教室格局改变，新增吧台，原报名处改办公室。网络，摄像头，电话重新布线以及设置 | 电话分机号码更新，网络端口增加，摄像头重新命名 |
| 2020/05/12 | 中山公园报名处一台组装机电源烧毁，更换一台HP Z238。 | 加装Sandisk SSD，480G |
| 2020/05/13 | 威宁校区教研室新安装1台 EPSON L6168 彩色喷墨打印机 | 原来的Canon G3800 因为装修，进了大量灰尘，故障（故障灯闪4下，应该是墨盒不能识别）|
| 2020/05/28 | 中山公园校区，更换主路由器: ER5200 -> ER8300G2-X | 前兆WAN口，可以适用于升级后的电信500M宽带 |
| 2020/11/03 | 威宁，古北，金沙江，中山公园校区报名处新增摄像头 | 新的摄像头，避免死角 |
| 2020/11/07 | 威宁小卖部新增 UAP AC Lite | 小卖部微信支付宝移动收费 |
| 2021/01/13 | 中山公园校区，新增一个教师办公室 | 7和网口，接在2F老教师办公室交换机，1个电话口（号码8208, 本来在2F老教师办公室里面小房间墙上双口面板，未用，移至新办公室) |
| 2021/02/02 | 金沙江校区人事薪资培训（多个教室直播）IT准备工作 | 1,2,33,35,36教室，每个教室使用电脑连接电视，进入腾讯会议，1，2号教室使用 HDMI HUB 进行3台小米电视投屏 |
| 2021/02/02 | 金沙江校区年会场地布置 | 大厅使用手机直播，35, 36教室每个教室使用电脑连接电视，进入腾讯会议，笔记本连接移动电视，播放PPT以及运行抽奖软件 |
| 2021/02/27 | chnmz/chnmz-pc分离2.4G/5G，新增chnmz-5G,chnmz-pc-5G | 关闭5G引导，更稳定，小米电视可以选择5G连接，投屏速度更快 |
| 2021/03/02 | 威宁所有小米电视，小米盒子4以及安装的乐播投屏App显示的投屏设备名称，重新命名，方便查找设备 | [小米电视，小米盒子，乐播投屏App投屏显示名称的命名规则](https://github.com/shchnmz/worklog/blob/master/hardware-and-network/doc/weining/tv-and-xiaomi-box.md#%E5%B0%8F%E7%B1%B3%E7%94%B5%E8%A7%86%E5%B0%8F%E7%B1%B3%E7%9B%92%E5%AD%90%E4%B9%90%E6%92%AD%E6%8A%95%E5%B1%8Fapp%E6%8A%95%E5%B1%8F%E6%98%BE%E7%A4%BA%E5%90%8D%E7%A7%B0%E7%9A%84%E5%91%BD%E5%90%8D%E8%A7%84%E5%88%99)  |

