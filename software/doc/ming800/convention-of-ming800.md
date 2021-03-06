# 明日系统信息输入约定

#### 背景
* 临时转班系统以及正在开发的教学管理后台需要从明日系统导入数据（年级，班级，学生...）
* 规范的信息输入可以确保数据导入的自动化
* 极大的减少人力输入，检查等工作量

#### 具体约定
* 年级命名
    * `年级` +`（校区）`。例子：`幼中（威宁）`
    * 不要出现`新`
    * 括号统一为**中文全角括号**

* 班级命名
   
    | 类型 | 命名规范 | 举例 |
    | ----| ---- | ---- |
    | 老班 | `班级名称` + `（校区）` | `三年级1（威宁）` |
    | 新班 | `2位年数` + `学期（秋／春）`+ `新`+ `班级名称` + `（校区）` | `17秋新基二三1 (威宁)` |

* 班级上课时间
  * 使用**自定义**时间。例如：`星期二 16:25-17:55` 
  * 严格和实际时间**保持一致**

* 一个学生同时报名2个或者2个以上班级
  * 使用选班的方法，不要添加新的学生

* 学生联系电话
  * 尽量输入11位中国手机号码
  * 如果要输入的电话号码已存在（明日系统限制：1个联系手机只能对应1个学生），不能输入的情况，约定如下:
    * 在号码末尾添加1个`.`（英文半角）

      例如: `13800138000.`      

    * 如果电话号码重复多次，则每次在末位再添加1个`.` 以此类推

      例如: `13800138000..` `13800138000...`
