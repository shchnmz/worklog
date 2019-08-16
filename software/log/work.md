# 工作日志

| 日期 | 事项 | 备注 |
| ---- | ---- | ---- |
| 2017/06/05 | 完成金税盘软件安装，金税盘固件升级。 | [升级金税盘底层固件的方法](https://github.com/northbright/Notes/blob/master/Software/caiwu/jinshuipan/update-jinshuipan-firmware.md) |
| 2017/07/03 | 完成[Unifi SDK](https://github.com/northbright/unifi) | 准备用于微信连WiFi的客制化来宾认证部分,地址: <https://github.com/northbright/unifi>，目前实现了Auth/Unauth功能 |
| 2017/07/17 | 完成微信公众号认证 / 微信小店 ／ 微信支付 | 古北校区小卖部 |
| 2017/09/21 | 完成上海个税申报，报税，网上认证三个软件数据导出导入 | [上海个税>申报，报税，网上认证三个软件数据导出导入](https://github.com/northbright/Notes/blob/master/Software/caiwu/geshui-baoshui-wangshangyanzheng-data-export-and-import.md) |
| 2017/10/20 | 完成eTax3@SH升级失败的修复 | [eTax@SH 3(网上电子申报)更新失败的解决方法](https://github.com/northbright/Notes/blob/master/Software/caiwu/eTaxSH3-failed-to-update/eTaxSH3-failed-to-update.md) |
| 2017/11/28 | 完成[在线转班申请系统](https://github.com/shchnmz/zb)，上线运行 | 提供了从明日系统导入学生，班级，时段等信息。家长申请转班流程简化：只需输入联系电话即可找到学生信息。提供禁止转班的时间段以及班级的列表支持。教导可以完全信任导出后的学生信息：联系方式，班级信息。 |
| 2017/12/01 | 完成古北校区小卖部（一思）微信小店升级微信小程序的认证 | 微信小店在2017/12月可以作为小程序 |
| 2018/03/13 | 完成[jwthelper](https://github.com/northbright/jwthelper)，用于用户认证模块 | 教师系统以及家长认证需要的通用模块 |
| 2018/03/26 | 完成[aliyun/message](https://github.com/northbright/aliyun/tree/master/message) | 用户新注册模块需要的短信验证码功能 |
| 2018/04/18 | 完成古北校区微信公众号认证(2018) | 古北校区小卖部 |
| 2018/09/01 - 2018/11/29 | 决定重新构建一个美校的IT系统，使用外包方案。工作包括:(1).前期准备讨论(2)内部首先需求分析(3). 流程图绘制(4). 和外包服务商会议，选择外包服务商 | |
| 2018/11/29 | 18年秋季的转班系统突然不能访问，查明是阿里云的CentOS 7的ECS的IP租约到期后刷新DHCP失败，没有获得内网IP，后联系客服重启网络服务后恢复 | [阿里云运行CentOS 7的ECS不能通过DHCP获取IP](https://github.com/northbright/Notes/blob/master/aliyun/can-not-get-ip-via-dhcp-on-centos-7-ecs.md) |
| 2019/03/01 - 2019/03/03 | 实现新的API，提供给第三方用于实现根据手机号码获取学生信息，课程，班级等信息用于学生基本信息采集项目 | <https://github.com/shchnmz/zb/tree/master/api> |
| 2019/03/08 | 学生基本信息采集项目上线 | 采集学生地区信息，用于对新校区的开班的提前统计与分析 |
| 2019/07/31 | 明日系统某个账号突然提示用户名密码不匹配（密码没有修改过） | [用户名冲突导致用户登录明日系统失败](https://github.com/northbright/Notes/blob/master/Software/ming/usernames-conflict-in-ming-cause-login-failure.md#%E7%94%A8%E6%88%B7%E5%90%8D%E5%86%B2%E7%AA%81%E5%AF%BC%E8%87%B4%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95%E6%98%8E%E6%97%A5%E7%B3%BB%E7%BB%9F%E5%A4%B1%E8%B4%A5)  |
| 2019/08/15 - 2019/08/16 | 网站备案提示信息不符，重新备案 | 5证合1后，代码变更，上海地区备案，主体负责人需要与法人一致，域名持有者需要与主办单位一致。[上海网站备案](https://github.com/northbright/Notes/blob/master/beian/shanghai-beian.md) |
