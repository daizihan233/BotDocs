# 这事什么？这事一个一个一个预告啊啊啊啊啊！
机器人马上就要迎来第 **3** 次大改了！<br>
所以所以所以期待罢啊啊啊啊！！！！！
# 警告 _（使用协议）_
!> 开发者 **没有** 解答问题的义务<br>
如果你觉得开发者 **有义务** 解决问题那么你应该 **立刻** 踢出机器人并关闭此文档，不要去 **浪费时间** 了<br>
因 **用户** 导致的问题且 **无正当理由或态度不符** 那么开发者 **一律不予解决**<br>
不会用可以不用，憋在这理发店<br>
如果你使用了那么默认你同意了这个警告<br>

!> 如果你能跟一个机器人争起来的话那你也没必要用了<br>
本人不是什么闲着蛋疼的人，没有充分的时间维护他，纯业余爱好<br>
本身就是用爱发电的东西，没有任何收入渠道，维护也是要成本的<br>
不要认为我没有事做！不要认为维护没有成本！不要认为我有义务解决你的任何问题！

?> 最后开个玩笑
![img_6.png](img_6.png)

# 这是个标题
?> 本文档使用 [Docsify](https://docsify.js.org/) 编写，文中会经常出现像这样的带链接的文字，不要怀疑我没放链接<br>

!> 机器人对符号尤为敏感，一个空格就是一个空格，不要多打也不要少打，发消息不要带回复！

!> \[xxx\] 表示可选参数，(xxx) 表示必填

?> 有问题小事 [Issue](https://github.com/daizihan233/Hanbot/issues) ，大事邮件 **hantools@foxmail.com** ，有QQ好友QQ说，没事儿别找我

# 开始

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

### 戳一戳
戳一戳机器人也会骂你一句

### 别骂我

!> 需要机器人管理

关闭此群祖安功能
### 快骂我

!> 需要机器人管理

开启此群祖安功能

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
!> 需要机器人管理员

?> @机器人 关键词撤回

自动判断开/关

?> @机器人 加新词 (xxx) <br>
@机器人 删词 (xxx)

加词与删词

## 图片审核
自动审核每一张图片

!> 本功能偏定制，请自己找开发者定制

政治敏感、色情、暴力、违法违规、广告、性感等图片可以自动撤回

### @机器人 safe (图片ID)
此功能用于将误判图片加白<br>
加白图片是不可能一劳永逸的（因为只是个缓存，而非永久存储），所以建议找开发者加进机器学习库中<br>

?> _**技术原因：**_ 纯色底色图片暂时无法加入机器学习库

### @机器人 clean (图片ID)
清除某张图片的缓存

### (From Redis, it's UNKNOW)
出现此提示表明这个图片的判定来源于数据库，所以属性未知<br>
~~好吧我承认是我偷懒没记~~
