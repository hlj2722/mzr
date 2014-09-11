Mzr
=========
基于Toropress衍生而来的图站源码.是Lihuashu.com的开发代号,
在阿里云上线后流量增速非常快,但鉴于国内的环境,运营一段时间后收到阿里云发出的照会,
此种类型的网站有政策风险,于是梨花树的图站版本被迫下线..

目前[Lihuashu.com](http://lihuashu.com)的域名已经跳转至sudochina.com,无法为你提供演示,请自行在本地编译尝鲜.

欢迎各位改进本项目源码,并反馈给我,谢谢大家一致以来的支持
,感谢那些捐助过本项目的用户,如需定制请联系我.


##轻量级社区版本

[YouGam社区](http://www.yougam.com/)

(类似V2EX,购买系统请联系作者QQ547092001)


##线上开源技术分享平台版本

[SudoChina](http://www.sudochina.com/)


## 企业型演示网站

[访问艾美](<http://www.ibeautys.com/>)

[访问因特拉](<http://www.interla.net/>)


## 实验性社区型演示网站

[访问 非常时刻 (Veryhour)](<http://www.veryhour.com/>)[演示站点已经下线]


## 图片分享社区演示网站

[访问 梨花树社区](<http://www.lihuashu.com/>)[演示站点已经下线]


# 通过捐款支持Toropress项目
如果你喜欢这个项目的话， 可以通过捐款的方式， 支持作者继续更新本项目或者做出其他更多好玩好用的开源应用： 比如为本项目修补漏洞、添加更多有趣的功能， 或者发行有更多更棒特性的下一版等等。

捐款支付宝邮箱地址： insion@live.com


## 感谢捐助或定制本项目的用户 排名按时间顺序
    右建华 5000,定制版
    李新友 5000,定制版 
    孙 300,捐助者要求不公开全名
    吕雷 2000,购买SDC源码
    高栋 5000,定制版

##第二版安装请先更新安装beego和xorm

    go get -u github.com/astaxie/beego
    go get -u github.com/lunny/xorm

##第一版安装请先更新torgo

    go get -u github.com/insionng/torgo

##安装
	先安装sqlite3驱动，譬如64位的win7：
	SQLITE3驱动编译环境是TDM版MINGW64(http://tdm-gcc.tdragon.net/)，
    安装好后请把TDM版MINGW64的bin目录路径加入到你的win7环境变量path里面。

	
	go get -u github.com/mattn/go-sqlite3

    下载toropress源码后解压并cd切换目录到 toropress目录下，然后执行go build app.go，编译好后，运行./app即可。
    默认用户:root,默认密码:rootpass




## 交流
欢迎大家加入QQ专用交流群:231956113/作者QQ：547092001

技术分享：[http://www.sudochina.com](http://www.sudochina.com)


## 授权许可
除特别声明外，本项目代码遵循[BSD 3-Clause License](<http://opensource.org/licenses/BSD-3-Clause/>)（3项条款的BSD许可协议）。


veryhour fork by toropress
==========================

A very special time website

这是未来社区网站的新模式探索项目~
基于[Beego](https://github.com/astaxie/beego)与[xorm](https://github.com/lunny/xorm)开发的GOLANG微博社区系统网站，从toropess源码衍生而来!


mzr fork by toropress
==========================

梨花树系统开发代号mzr

这是一个分享图片为主的社区系统~
基于[Beego](https://github.com/astaxie/beego)与[xorm](https://github.com/lunny/xorm)开发的GOLANG图片社区系统网站，从toropess源码衍生而来!

