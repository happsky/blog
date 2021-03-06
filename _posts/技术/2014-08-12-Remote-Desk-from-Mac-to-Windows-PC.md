---
layout: post
title: Mac远程桌面连接Windows
category: 技术
tags: Mac
keywords: 
description: 
---

在学习或者工作中，有时候需要远程控制Windows电脑。比如在家遇上暴雨天气，又急需使用办公室里的电脑，每当跋涉在雨中的时候，都希望可以远程控制。在生活中，也会有这样的时刻。比如远程帮助爸妈或者爷爷奶奶外公外婆解决一些电脑问题。

本文的目标就是，在完成所有步骤之后，可以从Mac OS X系统远程控制Windows电脑。

###准备工作：

- Mac一台
- Windows PC一台（这里用Windows 8系统的电脑）
- 互联网

###第一步：在Mac上安装Remote Desktop Connection
- 进入[Microsoft Remote Desktop Connection](http://www.microsoft.com/en-us/download/details.aspx?id=18140)下载安装包。
- 下载完成之后，双击安装包进行安装。

###第二步：在Windows电脑上设置“远程设置”
- 右键“`我的电脑`”，单击“`属性`”，单击“`远程设置`”
- 勾选“`允许远程协助连接这台计算机`”，勾选“`允许远程连接到此计算机`”
- 单击“`确定`”退出

###第三步：在Windows电脑上设置用户账户及密码（已设置过就跳过这一步）
- 进入“`控制面板`”，进入“`用户账户`”
- 设置账户名和密码，并牢记

###第四步：查看Windows电脑的IP地址
- 将鼠标移动至屏幕最右侧，出现命令条，单击“`搜索`”
- 输入“`cmd`”并回车，这样就打开了命令提示符
- 在命令提示符里输入“`ipconfig`”，回车
- 在输出中查看“`IPv4 地址`”后面的数字串，就是Windows本机的IP（比如我家的192.168.1.112）。

###第五步：从Mac远程桌面连接到Windows
- 回到Mac，打开第一步中下载并安装好的`Remote Desktop Connection`
- 窗口中输入第四步中查看到的Windows电脑IP地址（比如我就输入192.168.1.112）
- 点击“`连接`”
- 输入第三步里设置的Windows电脑的用户账户名和密码
- 点击“`确定`”（注意：在远程连接过程中Windows电脑必须保持开机状态，关机、待机或者锁屏状态都不行）

###恭喜，全部完成! ✌️
OK，现在就稍微等待一下，我们已经完成了从Mac远程桌面控制Windows电脑，大概30秒之后就可以身在合肥，操作远在重庆的Windows电脑了。或者看着暴雨中浑身湿乎乎的人们然后心中暗爽一下。


