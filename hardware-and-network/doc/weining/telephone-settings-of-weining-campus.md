# 威宁校区电话设置
  
#### 分机号码

| 位置 | 分机 | 对应年段 | 是否子母机 |
| :-- | :-- | :--: | :--: |
| 吧台报名处左起第1个 | 8001 | | 子母机 |
| 吧台报名处左起第2个，数字总机 | 8000 | | |
| 吧台报名处左起第3个 | 8002 | | 子母机 |
| 常务副校长/校长助理办公室（吧台后面） | 8003 | | |
| 吧台西侧新办公室（原报名处） | 8100 | | |
| 校长（老板)办公室 | 8005 | | |
| 门口第一间办公室第1个 | 8006 | | |
| 门口第一间公室第2个 | 8007 | | |
| 门口第一间办公室第3个 | 8008 | 素描 | 子母机 |
| 门口第一件办公室第4个 | 8009 | | |
| 教研室 | 8010 | 素描 | 子母机 |
| 教务处（内部4人小房间）| 8011 | | |
| 教务处（左），第2个座位 | 8013 | 幼儿 | 子母机 |
| 教务处（右），第3个座位（子母机连内部10人小间）| 8012 | 基础 | 子母机 |
| 财务室 | 8016 | | |
| 人事办公室 | 8015 | | |

#### 电话操作

|  功能 | 方法 |
|  :--- | :--- |
| 分机与分机互拨 | 直接输入分机号码 |
| 拨外线电话 | 按`9` |
| 分机拨总机 | 按 `0` |
| 总机响铃后，分机代接 | 按`*#`(注意：如果出现`*#`不能转接，可以尝试`*4001`) |
| 模拟电话转接（分机为模拟电话）| 1. 按`转接`／`R`/`闪断`/快拍`叉簧`(快速按下挂机的那个弹簧)，2. 输入`分机号码`， 3. 等待分机接起后挂断 |
| 配套松下数字电话转接（总机为数字电话) | 1. 按`Transfer`，2. 输入`分机号码`，3. 等待分机接起后>挂断 |
| 配套松下数字电话查看来电记录 | 1. 按`MENU`，2. 按`下箭头`，选择`Icoming Call Log`，3. 按`ENTER` |

#### 电话配线架端口与分机号码对应表
* 电话配线架共有4排：左上，左下，右上，右下
* 当前和松下电话程控交换机连接配置
   * 左上：连接模拟电话

      | 端口(Port) | 分机号码 | 位置 |
      | :--- | :--- | :--- |
      | 1 | 8001 | 报名处第3个 |
      | 2 | 8002 | 报名处第4个 |
      | 3 | 8003 | 报名处第5个 |
      | 4 | 8005 | 校长（老板)办公室 |
      | 5 | 8006 | 门口第一间办公室第1个 |
      | 6 | 8007 | 门口第一间办公室第2个 |
      | 7 | 8008 | 门口第一间办公室第3个 |
      | 8 | 8009 | 门口第一间办公室第4个 |
      | 9 | 8010 | 教研室 |
      | 10 | 8011 | 教务处（内部4人小房间） |
      | 11 | 8012 | 教务处（右），第3个座位 |
      | 12 | 8013 | 教务处（左），第2个座位 |
      | 13 | 8015 | 领导办公室 |
      | 14 | 8016 | 财务室 |
      | 15 | 8100 | 报名处第2个 |
      | 16 - 24 | 未使用，默认120 - 128 | n/a |

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
* MAC: `08:00:23:A5:DF:E0`
* 用户名: `INSTALLER`(大写)
* 初始密码: `2303`

#### 申瓯电话录音盒配置
* IP: `192.168.1.10`
* MAC: `70:B0:8C:82:D3:FD`
* 用户名: `admin`
* 初始密码: `123456`

#### 威宁校区电信盒电话线路配置
威宁楼道电信电话盒，蓝色网线分4门电话

4个号码前四位均一样

* 橙色：后四位:`5882`
* 蓝色：后四位:`5115`
* 绿色：后四位:`1388`
* 褐色：后四位:`1399`


#### 参考资料
* [Panasonic（松下）电话程控交换机操作](https://github.com/northbright/Notes/blob/master/hardware/panasonic/panasonic-kx-ns300-basis/panasonic-kx-ns300-basis.md)
