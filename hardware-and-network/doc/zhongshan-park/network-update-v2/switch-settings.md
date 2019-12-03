# H3C Switch Settings

## 核心交换机设置
* H3C S5500 48口
* VLAN: 1 2 3 4 6 10 20 21 22 100
* VLAN Interface:
  * VLAN 1: 10.0.1.1/24
* Trunk Ports
   * GE1/0/1 to GE/1/0/12
     * Permit VLAN: 1 2 3 5 6 20 21 22 100
     * 连接H3C 5120接入交换机
       * 级联到2楼/3楼办公室的交换机
       * 级联到机柜上的交换机
   * GE1/0/25
      * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
      * Port Trunk PVID VLAN 3
      * 级联接入交换机，连接老海康威视摄像头/录像机（教室）
   * GE1/0/26
      * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
      * Port Trunk PVID VLAN 5
      * 级联接入交换机，连接新海康威视摄像头/录像机（过道）
   * GE1/0/28
      * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
      * 级联H3C ER5200路由器LAN 1
* Access Ports
  * GE1/0/13 to GE1/0/14
    * Access VLAN 20
    * 连接有线设备，和无线设备同一个VLAN
  * GE1/0/15 to GE1/0/22
    * Access VLAN 10
    * 连接电脑
  * GE1/0/23 to GE1/0/24
    * Access VLAN 6 
    * 连接电话程控交换机，电话录音机 

## 2楼办公室接入交换机
* H3C S5120 48口
* VLAN: 1 2 3 4 6 10 20 21 22 100
* VLAN Interface:
  * VLAN 1: 10.0.1.15/24
* Trunk Ports
   * GE1/0/48
     * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
     * 级联核心交换机
   * GE1/0/45 to GE/1/0/47
     * Permit VLAN: 1 2 3 5 6 20 21 22 100
     * Port Trunk PVID VLAN 2
     * 连接AP 
* Access Ports
  * GE1/0/1 to GE1/0/44
    * Access VLAN 10
    * 连接电脑，打印机

## 2楼会议室接入交换机
* H3C S5120 24口
* VLAN: 1 2 3 4 6 7 10 20 21 22 100
* VLAN Interface:
  * VLAN 1: 10.0.1.16/24
* Trunk Ports
   * GE1/0/24
     * Permit VLAN: 1 2 3 5 6 7 10 20 21 22 100
     * 级联核心交换机
* Access Ports
  * GE1/0/1 to GE1/0/23
    * Access VLAN 10
    * 连接电脑

## 3楼办公室接入交换机
* H3C S5120 48口
* VLAN: 1 2 3 4 6 10 20 21 22 100
* VLAN Interface:
  * VLAN 1: 10.0.1.17/24
* Trunk Ports
   * GE1/0/48
     * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
     * 级联核心交换机
   * GE1/0/45 to GE/1/0/47
     * Permit VLAN: 1 2 3 5 6 20 21 22 100
     * Port Trunk PVID VLAN 2
     * 连接AP 
* Access Ports
  * GE1/0/1 to GE1/0/44
    * Access VLAN 10
    * 连接电脑，打印机

## 3楼校长室接入交换机
* H3C S5120 24口
* VLAN: 1 2 3 4 6 10 20 21 22 100
* VLAN Interface:
  * VLAN 1: 10.0.1.18/24
* Trunk Ports
   * GE1/0/24
     * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
     * 级联核心交换机
* Access Ports
  * GE1/0/1 to GE1/0/20
    * Access VLAN 10
    * 连接电脑
  * GE1/0/21 to GE1/0/23
    * Access VLAN 20
    * 连接有线设备，和无线设备同一个VLAN

## 3楼大办公室接入交换机
* H3C S5120 48口
* VLAN: 1 2 3 4 6 10 20 21 22 100
* VLAN Interface:
  * VLAN 1: 10.0.1.19/24
* Trunk Ports
   * GE1/0/48
     * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
     * 级联核心交换机
* Access Ports
  * GE1/0/1 to GE1/0/47
    * Access VLAN 10
    * 连接电脑

## 机房1号机柜第1个接入交换机
* H3C S5120 48口
* VLAN: 1 2 3 5 6 10 20 21 22 100
* VLAN Interface:
  * VLAN 1: 10.0.1.11/24
* Trunk Ports
   * GE1/0/48
     * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
     * 级联核心交换机
   * GE1/0/1 to GE1/0/46
     * Permit VLAN:  1 2 3 5 6 7 10 20 21 22 100
     * Port Trunk PVID VLAN 2
     * 连接AP
     * Port 46连接物业办公室
 * Access Ports
   * GE1/0/47
     * Access VLAN 2
     * 连接PC，安装UBNT Unifi Controller，在同一网段调试AP  

## 机房1号机柜第2个接入交换机
* H3C S5120 48口
* VLAN: 1 2 3 5 6 10 20 21 22 100
* VLAN Interface:
  * VLAN 1: 10.0.1.11/24
* Trunk Ports
   * GE1/0/48
     * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
     * Port Trunk PVID VLAN 3
     * 级联核心交换机 
* Access Ports
  * GE1/0/1 to GE1/0/47
    * Access VLAN 3
    * 连接老海康威视摄像头/录像机（教室）

## 机房2号机柜第1个接入交换机
* H3C S5120 48口
* VLAN: 1 2 3 5 6 10 20 21 22 100
* VLAN Interface:
  * VLAN 1: 10.0.1.13/24
* Trunk Ports
   * GE1/0/48
     * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
     * Port Trunk PVID VLAN 5
     * 级联核心交换机 
* Access Ports
  * GE1/0/1 to GE1/0/47
    * Access VLAN 5
    * 连接新海康威视摄像头/录像机（走道）

## 机房2号机柜第2个接入交换机
* H3C S5120 24口
* VLAN: 1 2 3 5 6 10 20 21 22 100
* VLAN Interface:
  * VLAN 1: 10.0.1.14/24
* Trunk Ports
   * GE1/0/24
     * Permit VLAN: 1 2 3 5 6 10 20 21 22 100
     * 级联核心交换机
   * GE1/0/1 to GE1/0/22
     * Permit VLAN:  1 2 3 5 6 7 10 20 21 22 100
     * Port Trunk PVID VLAN 2
     * 连接AP
 * Access Ports
   * GE1/0/23
     * Access VLAN 2
     * 连接PC，安装UBNT Unifi Controller，在同一网段调试AP

