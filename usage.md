
# AnswerotX详细使用帮助

**目前仅支持安卓手机，如没有安卓手机，可暂时安装安卓模拟器使用。**

## 使用方法

1. 拿出手机，进入设置，找到系统信息下的系统版本信息，一般连续点击7次打开手机开发者模式。

2. 再次进入设置页，找到已经开启的开发者模式选项，点击进入找到`USB调试`设置，勾选允许USB调试模式。

3. 拿出USB线连接手机和电脑，一般会在手机端提示`是否允许电脑调试手机`，选择允许即可。（**如果出现手机连接失败，应该是驱动安装失败，下载任意手机助手自动安装驱动，如[豌豆荚](http://www.wandoujia.com/)、[91助手](http://zs.91.com/)等**）

4. 下载[AnswerotX](https://github.com/anhkgg/answerotx/archive/master.zip)，点击运行`answerotx.bat`。根据提示信息填入手机设备号，如果没有找到设备号，请确认手机是否连上，USB调试模式是否打开，是否允许电脑调试手机。

```
请仔细查看下面的提示信息：

-----------------------示例设备信息------------------------------
List of devices attached
56939233 device        (若监控手机设备，下面输入56932933)
emulator-4444 host     (若监控该虚拟机，下面输入emulator-4444)

-----------------------实际设备信息-------------------------------
List of devices attached
* daemon not running. starting it now on port 5037 *
* daemon started successfully *
194f41e1        device   <<<< 这里就是你的手机设备，前面一串就是设备号

输入要控制的设备号\>194f41e1
AnswerotX: Start monitor < 194f41e1 >
AnswerotX: start...
```

5. 打开答题App，进入答题页面，打开浏览器访问[www.answerot.com](http://www.answerot.com)。等待手机app题目出现，点击浏览器中答题按钮，2秒左右出现结果。

# 说明

关于答案说明，请看[这里](https://github.com/anhkgg/answerot/blob/master/README.md)中`怎么答题`的说明。

由于目前不知道有多少朋友需要，[www.answerot.com](http://www.answerot.com)服务器配置较低，可能会影响速度，暂时只是提供体验使用，需要的可以跟我联系，我根据情况看是否升级服务器。如果动手能力强的朋友，可以自行下载[answerot](https://github.com/anhkgg/answerot)配置自己的服务器。

answerot支持直接在线使用，不需要AnswerotX，也兼容AnswerotX同事使用。

**关于模拟器？**

请看[这里](https://www.zhihu.com/question/20863016)自行选择模拟器，如何配置安装也请自己百度一下。


