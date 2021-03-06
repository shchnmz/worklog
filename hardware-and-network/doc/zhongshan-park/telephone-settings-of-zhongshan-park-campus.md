# 中山公园校区电话设置(2018/02/05)

#### 分机号码

| 位置 | 分机 |
| :-- | :-- |
| 2F报名处第1个 | 8209 |
| 2F报名处第2个(数字总机:接2门外线) | 8201 | 
| 2F报名处第3个 | 8207 |
| 2F报名处第4个(主任) | 8200 |
| 2F教务处（左）| 8202 |
| 2F教务处 (右) | 8205 |
| 2F教务处（内部小房间副校长）| 8203 |
| 2F教务处（内部小房间市场部）| 8208 |
| 2F小卖部 | 8206 |
| 3F校长室 | 8301 |
| 3F教务处（左）| 8302 |
| 3F教务处（右）| 8303 |
| 3F教务处（内部小房间）| 8305 |

#### 电话操作

|  功能 | 方法 |
|  :--- | :--- |
| 分机与分机互拨 | 直接输入分机号码 |
| 拨外线电话 | 按`9` |
| 分机拨总机 | 按 `0` |
| 总机响铃后，分机代接 | 按`*#` (注意：如果出现`*#`不能转接，可以尝试`*4001`)|
| 模拟电话转接（分机为模拟电话）| 1. 按`转接`／`R`/`闪断`/快拍`叉簧`(快速按下挂机的那个弹簧)，2. 输入`分机号码`， 3. 等待分机接起后挂断 |
| 配套松下数字电话转接（总机为数字电话) | 1. 按`Transfer`，2. 输入`分机号码`，3. 等待分机接起后>挂断 |
| 配套松下数字电话查看来电记录 | 1. 按`MENU`，2. 按`下箭头`，选择`Icoming Call Log`，3. 按`ENTER` |
| 配套松下数字电话机2根外线设置忙转（1根外线拨进用数字总机接起后，另1根外线拨进后转到分机响铃）| 按`*7105` + `分机号` + `#` |

#### 电话配线架端口与分机号码对应表
* 电话配线架共有4排：左上，左下，右上，右下
* 当前和松下电话程控交换机连接配置
   * 左上：连接模拟电话
      
      | 端口(Port) | 分机号码 | 位置 |
      | :--- | :--- | :--- |
      | 1 | 8202 | 2F教务处（左）|
      | 2 | 8203 | 2F教务处（内部小房间）|
      | 3 | 8205 | 2F教务处 (右) |
      | 4 | 8206 | 2F小卖部 |
      | 5 | 8301 | 3F校长室 |
      | 6 | 8302 | 3F教务处（左） |
      | 7 | 8303 | 3F教务处（右） |
      | 8 | 8305 | 3F教务处（内部小房间） |
      | 9 | 未使用，默认113  | n/a |
      | 10 | 8207 | 2F报名处模拟电话 |
      | 11 | 8200 | 2F报名处主任分机 |
      | 12 - 24 | 未使用，默认116 - 128 | n/a |
      
   * 左下：连接数字电话
  
     | 端口(Port) | 分机号码 | 位置 |
     | :--- | :--- | :--- |
     | 1 | 8201 | 2F报名处数字总机 |
     | 2 | 未使用，默认102 | n/a |
   
   * 右下：外线
      * 1 - 6：外线1 - 6
      * 当前接入1，2外线
        * 2条外线接入松下电话程控交换机

#### 松下程控交换机远程登录增加/修改分机号码
1. 由网络管理员根据标签上的LAN的MAC分配静态IP地址（e.g. 192.168.1.9)
2. 在浏览器输入电话程控交换机的 IP
3. 输入用户名和密码。初始用户名为`INSTALLER`（大写），初始密码为`2302`
4. 左侧点击`Extension` -> `1. Wired Extension`
    * 序号`1`，`2`是数字电话使用的分机号码(`DPT`)
    * 序号`3`，`4`是保留给数字电话使用
    * 序号`5`开始是模拟电话（`SLT`）
    * Port是对应电话配线架上的Port口，如果增加分机线路，先在配线架上的Port口打上，再找到对应Port，设
置分机号码

#### 松下程控交换机配置
* IP: `192.168.1.9`
* MAC: `08:00:23:A5:D4:F7`
* 用户名: `INSTALLER`(大写)
* 初始密码: `2303`

#### 申瓯电话录音盒配置
* IP: `192.168.1.90`
* MAC: `70:B0:8C:83:09:05`
* 用户名: `admin`
* 初始密码: `123456`

#### 参考资料
* [Panasonic（松下）电话程控交换机操作](https://github.com/northbright/Notes/blob/master/hardware/panasonic/panasonic-kx-ns300-basis/panasonic-kx-ns300-basis.md)
