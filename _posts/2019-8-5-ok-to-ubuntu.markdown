---
layout: post
title: 搭建Ubuntu虚拟机难点分享
tags: VM
comments: true
---

经历了重重险阻，我终于算是搭建好了Ubuntu。
我把我的困难向大家分享一下，不要到时候重蹈我的覆辙。



- 1.虚拟机BIOS没启动。
方案，重启，f10，BIOS界面，vt，true即可
- 2.虚拟机打不开。
把Vmware 15 workstaion pro
卸载，下载VMWARE 15 player
- 3.Ubuntu中文没打开。
到language setting里自己操作
- 4.输入法无中文。
进入Firefox，搜索sougoupinyin for Linux
进入下载。重启，右上键盘调整即可。
- 5.不自带git
进入终端 sudo apt install git
- 6.没有root权限
命令前输sudo.
差不多啦
