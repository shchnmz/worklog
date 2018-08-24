# 美校服务器共享文件夹以及共享打印机连接指南

## 确认登陆用户密码不为空
如果密码为**空**，由于策略原因将**不能**连接服务器共享文件夹

* 确认步骤
  * 如果开机没有输入密码直接登陆系统，则密码为空
* 修改用户密码步骤
  1. 同时按下`ctrl` + `alt` + `del`
  2. 选择`更改密码`
  3. 跳过原密码（因为空) ,设置新密码,确认新密码
      * 建议统一`123456`，方便后期别人维护登陆

## 连接服务器
1. 打开`计算机`(Win7)或者`文件资源管理器`(Win10)
2. 在**地址栏**点击一下，鼠标双击，全部选择(变成蓝色)
3. 在**地址栏**输入`\\服务器名`, 具体`服务器名`见下表

    | 校区 | 服务器名 | 地址栏输入 |
    | :--: | :--: | :--: |
    | 威宁 | `server` | `\\server` |
    | 中山 | `server1` | `\\server1` |
    
4. 回车，如果弹出"输入用户名/密码", 见下表
    
    | 校区 | 服务器名 | 地址栏输入 | 用户名 | 密码 |
    | :--: | :--: | :--: | :--: | :--: |
    | 威宁 | `server` | `\\server` | `\server\my` | `123456` |
    | 中山 | `server1` | `\\server1` | `\server1\my` | `123456` |

## 在桌面创建共享文件夹的快捷方式
* Win7: 鼠标**右键**点击共享的文件夹 -> `发送` -> `创建桌面快捷方式`
* Win10: 鼠标**右键**点击共享的文件夹  -> `创建快捷方式` -> `要把快捷方式放在桌面上吗?` -> `是`

## 连接服务器的共享打印机
* 鼠标**右键**点击共享打印机 -> `连接`
   耐心等待操作完毕，结束后打印机就会出现在`设备和打印机中`，打印文档的时候选择该打印机即可

