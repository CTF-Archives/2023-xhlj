# 第七届西湖论剑·中国杭州网络安全技能大赛 初赛

## Web

### only_sql

> 说了随便连啦就是随便连，你输什么我都不管的。
>
> hint:LOAD DATA

### ezinject

> ezinject

### ezerp

> ezerp  
>
> hint1: plugins目录不存在
>  
> hint2: 附件新增一个 [https://xjlh2024-1308232561.cos.ap-nanjing.myqcloud.com/WEB-ezerp.jar](https://xjlh2024-1308232561.cos.ap-nanjing.myqcloud.com/WEB-ezerp.jar)

### ezupload

> ezupload  
>
> 链接：[https://pan.baidu.com/s/1PCl4DzkbMqXIy92x9xseQw](https://pan.baidu.com/s/1PCl4DzkbMqXIy92x9xseQw)  提取码：DASC
>
> hint1: 附件下载地址新增一个 [https://xjlh2024-1308232561.cos.ap-nanjing.myqcloud.com/WEB-ezupload.jar](https://xjlh2024-1308232561.cos.ap-nanjing.myqcloud.com/WEB-ezupload.jar)

### Easyejs

> 我的第一个nodejs项目

## Misc

### 2024签到题

> 那么，暗号在哪呢？(本次比赛赛题格式一般为 DASCTF{xxx}/flag{xxx}格式，提交时只需要提交括号内内容，比如此处就是xxx，如有特殊情况会在题目中说明)

### easy_tables

> 某公司的数据安全工程师在对数据库日常审计时，发现部分账号进行了违规操作。 现该工程师从数据库中导出了四张表：  
>
> 1. 表“users.csv”是账号表，记录着账号密码和所属权限组编号，其中的“所属权限组编号”列对应表“permissions.csv”的编号，表示该用户归属对应的组别中
>
> 2. 表“permissions.csv”是权限组别对应表，其中的“可操作表编号”列对应表“tables.csv”的编号，表示该组别对可操作的表具有一定的权限操作，便于管理用户对数据库表的访问权限，以便控制他们可以执行的操作
>
> 3. 表“tables.csv”中“可操作时间段”列说明在规定的时间段内可对相应的表进行操作
>
> 4. 表“actionlog.csv”是具体操作日志表，记录着具体账户执行的数据库操作。  具体示例请参考附件中“样例”文件夹中的“样例说明.pdf”。  
>
> 请选手根据这四张表协助数据安全工程师开展数据库操作分析，从中找到违规操作，违规操作包括不存在的账号执行了操作、账号对其不可操作的表执行了操作、账号对表执行了不属于其权限的操作、账号不在规定时间段内执行了操作。将找到的违规操作位于表中的编号用下划线(_)拼接。若不存在的账号执行了操作，则只保留在actionlog.csv表里的编号，其余编号用0代替。若有多个恶意操作，编号之间用逗号(,)隔开即可，拼接顺序依次按照在  users.csv、permissions.csv、tables.csv、actionlog.csv  表中的编号顺序进行排序，最后将拼接后的内容进行32位小写md5加密处理，提交格式为flag{md5(xxxx)}。
>
> 例如经分析后得到的结果为  abc123，通过计算 md5('abc123')=e99a18c428cb38d5f260853678922e03，则提交的答案为  e99a18c428cb38d5f260853678922e03。

### easy_rawraw

> easy raw! many passwords!  
>
> 链接：<https://pan.baidu.com/s/1ugNPdYW60aqCOtnSY95tdw?pwd=DASC>  提取码：DASC  --来自百度网盘超级会员V5的分享

## Crypto

### Or1cle

> 蒸馍会是，又是签到! :D

### Or2cle

> 签到题！ :D  
>
> hint:附件中proof是被修改过的，不影响做题

### Or3cle

> 太好啦，都是签到题！ :D

## Reverse

### Qrohttre

> None

### MZ

> flag为一段有意义的文本

### BabyCPP

> Just CPP

## Pwn

### Privilege_1

> 小明认为系统无懈可击  
>
> hint：请关注系统的systemd service

### babywin

> hint：no DEP and attack SafeSEH

### Privilege_2

> 小明说它在这个系统修复了一些漏洞，它变安全了？

## IOT

### easygateway

> easygateway to getshell  
>
> hint：diff

### hardgateway

> None

## 数据安全

### Cyan-1

> <http://exam.cyan.wetolink.com>  
>
> flag1答完题就有。  
>
> 这里是 flag1 提交处，flag格式为 DASCTF1{***}, 只提交括号内的字符串。  
>
> 温馨提醒：千万不要对这个题使用扫描器，一扫描IP会被封5分钟。此题不需要扫描器。

### Cyan-2

> flag2，登录管理员后台，看用户列表就有了。  
>
> 这里是 flag2 提交处，flag格式为 DASCTF2{***}, 只提交括号内的字符串。  
>
> PHPEMS源码下载分流：链接：<https://pan.baidu.com/s/1qK5ox8s4zknefQGsxSWy2g?pwd=DASC>   提取码：DASC  --来自百度网盘超级会员V5的分享  
> hint1: 1. 管理员账号在靶机里已经改过了，教师账号也删了，不要刻舟求剑，自己想其他办法吧，谢谢。 2.新增附件下载地址一个  <https://xjlh2024-1308232561.cos.ap-nanjing.myqcloud.com/%E6%95%B0%E6%8D%AE%E5%AE%89%E5%85%A8-Cyan-2.zip>  
>
> hint2: CVE-2023-6654

### Cyan-3

> flag3，RCE 了就有了。  
>
> 这里是 flag3 提交处，flag格式为 DASCTF3{***}, 只提交括号内的字符串。
>
> hint3: 想办法把 key 捞出来，然后反序列化，当然不一定好像也不能直接RCE，心不要太急，要长期主义。

### Cyan-4

> flag4, 在笔记本的加密文档里。  
>
> 这里是 flag4 提交处，flag格式为 DASCTF4{***}, 只提交括号内的字符串。

### Cyan-5

> flag5，在密码库里。  
>
> 这里是 flag5 提交处，flag格式为 DASCTF5{***}, 只提交括号内的字符串。
