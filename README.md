# DAX-Studio-Guide

我们将在这里介绍DAX Studio的功能，使用和相关技巧，主要来源于官网的英文资料。也会有一些使用案例和源代码分析。本文大部分文档都来自于[官网](http://daxstudio.org/documentation/)，只是将其翻译为中文，并辅助将个人文章和收集的文章进行汇总。

 [功能列表](https://github.com/asxinyu/DAX-Studio-Guide/blob/master/Features.md) | [视频](http://daxstudio.org/documentation/videos/) | [安装](https://github.com/asxinyu/DAX-Studio-Guide/blob/master/Installation.md) | [故障排除](http://daxstudio.org/documentation/troubleshooting/)

# 1.DAX Studio介绍
DAX Studio是一个在Power BI,Power Pivot分析中，编写、执行和分析DAX查询表达式的开源工具,使用C#语言编写。DAX是PowerBI的灵魂，所以DAX Studio的出现极大的简化了学习和使用成本。

DAX官网：http://daxstudio.org/

安装包下载：http://daxstudio.org/downloads/

Github地址：https://github.com/DaxStudio/DaxStudio


# 2.DAX Studio文档
## 2.1 主窗口
![如下图所示，是DAX Studio的主屏幕：](https://raw.githubusercontent.com/asxinyu/DAX-Studio-Guide/master/Img/DaxStudio_MainScreen.png)
主窗体功能介绍：

1.[功能区控件](http://daxstudio.org/documentation/features/ribbon-control)/[文件菜单](http://daxstudio.org/documentation/features/file-menu)

2.[元数据面板](http://daxstudio.org/documentation/features/metadata-panes)

3.[查询编辑器](http://daxstudio.org/documentation/features/query-editor)

4.[输出面板](http://daxstudio.org/documentation/features/output-panes)

5.[状态栏](http://daxstudio.org/documentation/features/statusbar)

## 2.2 主要功能特点
DAX Studio可以作为插件在Excel 2010/2013中使用，是一个独立的程序，提供了一下一些功能：
- 优雅的用户界面
  - [灵活布局]((http://daxstudio.org/documentation/features/flexible-layout))
  - [支持选项卡](http://daxstudio.org/documentation/features/multiple-tabs)
  - [仿Office 2013 Raibbon控件](http://daxstudio.org/documentation/features/ribbon-control)

- 集成跟踪
  - [查询计划跟踪](http://daxstudio.org/documentation/features/query-plan-trace)
  - [服务器定时跟踪](http://daxstudio.org/documentation/features/server-timing-trace/)
- [新版本通知](http://daxstudio.org/documentation/features/new-version-notification/)
- [独立安装](http://daxstudio.org/documentation/installation/single-installer)

## 2.3 相关开源项目
Dax Studio使用了下面的一些开源下面,没有这些下面的支持,也没有现在的DAX Studio：

[AvalonEdit](http://avalonedit.net/) - main editor control

[AvalonDock](http://wpftoolkit.codeplex.com/) (part of Xceed WPF Toolkit - Community Edition) - Docking UI

[Caliburn.Micro](http://caliburnmicro.codeplex.com/) - MVVM framework

[Fluent Ribbon](http://fluent.codeplex.com/) - Ribbon control and Office 2013 window style

[Hardcodet NotifyIcon](http://www.hardcodet.net/wpf-notifyicon) - version update notification messages

# 3.相关文章资源
1.微软Power BI官网学习资料：[链接](https://docs.microsoft.com/zh-cn/power-bi/service-get-started)

2.PowerBI大师-马世权：[DAX学习分享：十条经验](https://mp.weixin.qq.com/s/UXVJLEk3kcnKhChLlQyhsA)

3.PowerBI极客-高飞：[认识DAX数据分析语言](https://mp.weixin.qq.com/s/WimTFi_Tt7-EPx-Kc6H4aw)

4.马世权，[PowerBI的M与DAX之争](https://zhuanlan.zhihu.com/p/27416587)

5.董斌辉，[DAX语法规范,思维导图](https://mubu.com/edit/g8ojIiXFB)

6.BI佐罗, [DAX查询入门：DAX Studio介绍](https://mp.weixin.qq.com/s?__biz=MzI1MDA4MzcxMA==&mid=2650781367&idx=1&sn=e8f55f7c9d02355318ec000e9f88dbf0&chksm=f18cb6a6c6fb3fb0235c40289ec8a07c55556941668cba1ff63afa92080c01f13e69d291afbf&scene=21#wechat_redirect)

7.BI佐罗,[Power BI DAX 终极调校工](http://mp.weixin.qq.com/s/8HdHljN7Anhipl6akfuUXA)

8.BI佐罗,[DAX查询进阶：驾驶DAX Studio](https://mp.weixin.qq.com/s/nWqrV3OXZKp1T2rCRv8bJw)


# 4.Power BI公众号
1.PowerBI大师,微信号:PowerBIMaster

2.数据挖掘助手,微信号:DataMiningHelper

3.PowerBI极客,微信号:

4.PowerPivot工坊,微信号:PowerPivotWorks

5.Excel120PowerBI,微信号:excel120

#5.联系我
如果您有好的建议,可以和我联系：

E-mail: asxinyu@qq.com

QQ:1287 2637 03

WebChat:PowerDataWorld
