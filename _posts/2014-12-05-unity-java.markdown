---
layout: post
title:  "Unity 与 Android Java 互调通信"
date:   2014-12-05 10:18:00
categories: Essay
---


前几天朋友游戏公司的游戏急于接入UC国内渠道商平台，就顺便过去帮忙做了几天游戏与UC SDK接入工作。

###准备工作

下载熟悉UC SDK渠道平台的各类接入文档、有几个功能：初始化、登录、炫富按钮、充值体系、退出SDK;
下载UC SDK包、下载unity的class.jar用于Unity与android通信互调用的

###新建Android项目

新建Android项目，把CLASS.JAR复制到项目libs文件夹中,按SDK开发文档要求进行环境配置，将 MainActivity extends UnityPlayerActivity ，
将需要调用的安卓SDK方法写好。AndroidManifest.xml根据91SDK的要求进行配置。

###Unity项目工作

导出Android项目的jar包，在Unity项目里的ASSETS文件夹下新建文件夹Plugins,在Plugins文件夹中新建Android文件夹，在Android文件夹中新建bin文件夹和libs文件夹，将Android打好包的
jar复制到bin文件夹中，将91SDK的libs文件夹下想要用到的jar包全部复制到libs文件夹中，将91SDK的res文件夹全部复制到Android文件夹中，将Android项目的AndroidManifest.xml复制到ANDORID文件夹下，把Android项目中的资源按照对应的文件夹复制到UNITY项目RES文件夹的对应文件夹内。

###Unity打包工作

根据Unity游戏自身打包流程进行打包，安装，测试、OK

