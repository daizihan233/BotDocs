# 这是个标题
?> 本文档使用 [Docsify](https://docsify.js.org/) 编写，文中会经常出现像这样的带链接的文字，不要怀疑我没放链接<br>

!> 机器人对符号尤为敏感，一个空格就是一个空格，不要多打也不要少打，发消息不要带回复！

!> \[xxx\] 表示可选参数，(xxx) 表示必填

?> 有问题小事 [Issue](https://github.com/daizihan233/Hanbot/issues) ，大事邮件 **hantools@foxmail.com** ，有QQ好友QQ说，没事儿别找我

# 明写在菜单上的功能

菜单调用方法：
```message
@机器人
```

## ~~help~~ _（已弃用，将在后续版本移除）_

就如他的名字一样，获取每个功能的用处即用法<br>

?> 语法：<br>
@机器人 help (xxx)<br>
@机器人 help<br>

语法一：查询某一个功能<br>
语法二：查询 help 用法

## 咕咕咕

娱乐性功能，语法参考下图，本质只是一个数字的无意义自增<br>

![img.png](img.png)

## 黑名单

!> 需要机器人的管理员

可以将一个人加黑到黑名单，没啥用，仅仅是加进去而已……<br>
类似自动踢出等偏定制性的功能可以找我

?> 语法：<br>
@机器人 黑名单 (QQ号: 数字)<br>
@机器人 黑名单 (@xxx)<br>

## 加群自动同意

用的人比较少…… 所以是直接写死在代码里的，后续版本会陆续支持直接使用消息控制

## 特定关键词复读

娱乐性功能<br>

![img_1.png](img_1.png)

像上面这样，复读的词可以用
```message
@机器人 help 特定关键词复读
```
查看

## 来份面包

![img_2.png](img_2.png)

就如上面这样<br>
面包会随着时间慢慢变多，1024个封顶

?> 语法自己看（

## 聊天

人工智障…… 非连续性聊天<br>

?> @机器人 (xxx)

## 祖安

!> 一小时最多使用五次

### 祖安我
让机器人骂你一句

### 祖安屑
同样是让机器人骂你一句。。。

### 祖安(@xxx)
让机器人骂被@的人一句

## 申请管理员
找我就行，看那个干嘛（

!> 如果出现滥用开发者有权直接下掉你的权限

!> 审核相对较严，不一定 100% 通过

## 百度

?> @机器人 百度 (xxx)

机器人会发个网站<br>
让我帮您百度一下.gif

## 哔哩哔哩
和上面那个用法一样

## pi
娱乐性功能，让机器人 **估算** 一下Pi，~~当然从来没有准过~~<br>
~~据说可以拖慢机器人的服务器~~

## 突发恶疾
生成发病小作文

?> @机器人 突发恶疾 (xxx)

## 鸡汤
让机器人说一句心灵鸡汤，没什么用。。。

?> 鸡汤

## 运行状态
告诉你机器人现在运行得咋样，仍然没什么卵用（

![img_3.png](img_3.png)

?> @机器人 运行状态

## 禁言
!> 本功能属于 **可被滥用指令**<br>
**需要机器人管理员，操作者不必是群管理员**<br>
可能会造成滥用，如果发现滥用可以找我

!> 如果出现滥用开发者有权直接下掉你的权限

?> @机器人 禁言 (QQ号/@xxx) \[时长/分钟，默认 11 天 4 小时 51 分钟 4 秒\]

## 解禁

解除禁言，和上面那个禁言一样 属于 **可被滥用指令**，**需要机器人管理员**

## 论证
恶臭数字论证器，娱乐性

?> @机器人 论证 (xxx: 数字)

![img_4.png](img_4.png)

## 清屏
**需要机器人管理员权限**

!> 本功能属于 **可被滥用指令**<br>
可能会造成滥用，如果发现滥用可以找我

!> 如果出现滥用开发者有权直接下掉你的权限

发一堆换行，就清屏了（迫真

## 播放音乐

?> @机器人 播放音乐 \[xxx，默认网易云歌曲榜的TOP1\]

## 面包库存
查看面包库存，没啥用

## 给你面包
?> 语法见图

![img_5.png](img_5.png)

本功能对标点不敏感，所以出现标点不会使得其报错<br>
譬如 **114.514** 仍然会识别成 **114514**

## 删黑
删除黑名单，需要机器人管理员

# 没写在菜单上的（我懒）
## 主页
查询B站主页<br>
支持昵称检索和UID检索

?> 主页-(xxx/UIDxxx)

## 心理疏导
其实就是给你一堆号码而已（（（

## 我想自杀
出现类似的话语机器人会安慰你<br>
~~不过这好像没什么用吧~~

## 关键词撤回
呃…… 这个词库太强大了，好多词不给说<br>
消息控制在做了，别催了别催了（
