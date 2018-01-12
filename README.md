# million-hero
百万英雄，自动搜题程序

**最近全民答题比较火爆，比如百万英雄，冲顶大会，芝士超人等，让普通民众也感受了一把心跳。**

#Update
> - 2018-01-11 汉王ORC太贵不够用，切换到百度云[文字识别](http://ai.baidu.com/docs#/OCR-API/top)，每天500次免费额度
> - 2018-01-10 ORC采用阿里云汉王文字识别

**百度ORC识别appkey改一下，人多500次也不够，如下图**

![1.png](res/3.png)

- QQ吃鸡交流群

<img width=300 src="res/qun.png"/>

> 本程序参考了一下，最近比较火的跳一跳的原理
1. 安卓手机调试模式
2. 截图
3. 截取文字部分
4. ORC文字识别
5. 调用百度，返回查询结果
6. 一道题平均查询时间不到3秒

### 现隆重介绍一下实现的语言工具 [AARDIO](http://bbs.aardio.com/) 一位国内老程序员开发的语言。[介绍点这里](http://bbs.aardio.com/portal.php?mod=view&aid=5)
- 引用官方的介绍
> aardio 专用于桌面软件快速开发，开发环境仅 6.5 MB, 绿色软件解压即用 -  无论个人或企业都可以永久免费使用本软件开发商用、或非商用的应用程序。使用aardio开发的软件不需要放置鸣谢链接、不需要声明使用aardio开发。 

- 讲真aardio非常强大，很实用，入门简单，比python、node来说简单不少，非常适合开发windows程序

**使用方法如下**
1. 开启usb调试模式安卓手机一部
2. 安装ADB调试驱动 [下载](http://www.wmzhe.com/soft-39913.html)
3. 配置windows环境变量，把adb解压完整目录名加入PATH
4. 双击运行MillionDollar.exe [下载](https://github.com/zsj1029/MillionHero/files/1622190/Publish.zip)

![1.png](res/1.png)

- 手机连接成功如上图显示，否则就去看看adb调试相关的连接知识，这里就不多做介绍

![screenshot.png](res/screenshot.png)

- 根据提示，当题目出现后，按下回车开始识别搜题

![2.png](res/2.png)

- 程序会去百度查询，返回前几条数据直接显示
- 之后我不用我介绍了，多练习练习反应能力
- 预祝大家大奖拿到手软

![screenshot.png](res/alipay.png)
- 吃水不忘挖井人，支付宝给个打赏，金额随意


