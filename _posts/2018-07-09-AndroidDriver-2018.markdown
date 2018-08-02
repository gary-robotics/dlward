---
layout:     post
title:      "AndroidDriver"
subtitle:   "android"
date:       2018-07-19 12:00:00
author:     "Edlward"
header-img: "img/post-bg-2015.jpg"
header-mask: 0.3
catalog:    true
tags:
    - android
---
# 路线
[如何选择单片机和Android-LInux-ARM开发板？](https://www.zhihu.com/question/41812528)  
[嵌入式开发职业课程](http://www.makeru.com.cn/roadmap/emb)   

# OPENCV 
[OpenCV移植到ARM全过程-III](https://blog.csdn.net/kaychangeek/article/details/78552418)  
[tiny4412移植opencv2.4.7手记](https://blog.csdn.net/u010606097/article/details/41316271)    
[OpenCV结合V4l2实现人脸检测](https://blog.csdn.net/wr132/article/details/54564044)  
[V4l编程以及Qt相关应用](https://blog.csdn.net/wr132/article/details/54348465)  

# Camera
[S5PV210 camera 驱动分析（android）](https://blog.csdn.net/liuying_0408/article/details/7532470)  

# Android Driver  
[ARM Tiny210v2开发板Android系统读写串口设备](https://blog.csdn.net/chenxupro/article/details/12249641)  
[FriendlyARM Tiny210v2 SPI接口Android平台测试](https://blog.csdn.net/chenxupro/article/details/8746544)  
[哇咔咔！用Android手机控制电脑](https://blog.csdn.net/chenxupro/article/details/7225530)  
[和菜鸟一起学android4.0.3源码之wifi的简单分析](https://blog.csdn.net/andrinux/article/details/38418243)  
[Android驱动（一）硬件访问服务学习之（一）Android通过JNI访问硬件](https://blog.csdn.net/fengyuwuzu0519/article/details/55224423)  
[Android驱动（一）硬件访问服务学习之（一）Android通过JNI访问硬件](https://blog.csdn.net/fengyuwuzu0519/article/details/55224423)  



## LINUX QT  
[Android应用程序通过JNI调用驱动程序(友善Smart210)](https://blog.csdn.net/xie0812/article/details/19628109)  
[Android 源码编译及常见错误及解决方法](https://www.cnblogs.com/kyyblabla/p/3603931.html)  
[Ubuntu12.04 制作Smart210的编译环境](https://blog.csdn.net/kanchuan1905/article/details/51239702)  
[Smart210一键部署运行qt程序](https://blog.csdn.net/westlor/article/details/50481109)     
[Qt-5.3.2 在友善Smart210开发板的移植记录](https://blog.csdn.net/newthinker_wei/article/details/39560109)  
[车载实时路况信息接收终端移植于Smart210开发板 --- 综合教程](https://blog.csdn.net/geng823/article/details/31898369)    
[Qt移植以及QT creator一键调试](https://blog.csdn.net/kunkliu/article/details/78740933)   
[关于友善之臂Tiny210电容屏移植tslib](https://blog.csdn.net/embed_coder/article/details/52156427)  
[移植 Qt 至 tiny210 详细过程](http://www.cnblogs.com/GyForever1004/p/8955665.html)  
[tiny210 tslib 测试（基于 ft5x06 触摸屏），解决触摸无效问题](https://www.cnblogs.com/GyForever1004/p/8955673.html)

## LINUX 根文件系统    


## Linux Driver
[linux的串口驱动分析](https://www.cnblogs.com/chd-zhangbo/p/5410336.html)    
[/etc/init.d/rcS内容分析](https://blog.csdn.net/bailyzheng/article/details/7487359)  
[qemu搭建kernel学习环境](https://blog.csdn.net/kevin_mr/article/details/52754757)    
[OK210-uvc摄像头采集并显示在屏幕上（v4l2编程）](https://blog.csdn.net/kevin_mr/article/details/51470215)  
[Linux 下V4l2摄像头采集图片，实现yuyv转RGB,RGB转BMP，RGB伸缩，jpeglib 库实现压缩RGB到内存中，JPEG经UDP发送功](https://blog.csdn.net/xuyangwyw/article/details/40476653)  
[设备模型(device-model)之平台总线（bus），驱动（driver），设备（device）](http://www.cnblogs.com/hackfun/p/5951235.html)  
[基于Linux3.0.8+smart210的DS18B20驱动移植](https://blog.csdn.net/gz_go/article/details/45952879)  
[Smart210学习-----lcd驱动](https://www.cnblogs.com/qigaohua/p/5469192.html)  
[移植tiny210的 触摸屏驱动](https://blog.csdn.net/u014600130/article/details/35268873)  


## LINUX 项目   
[基于S5pv210流媒体服务器的实现之网络摄像头](https://blog.csdn.net/liukun321/article/details/24390379)  
[串口编程](https://wenku.baidu.com/view/152473048e9951e79b8927cc.html)  
[ARM（s5pv210）采用V4L2采集USB摄像头图像，送入OPENCV做图像识别，然后经过h264硬件编码后经过ORTP编码通过wifi传输到PC端，在vlc媒体播放器实时播放视频-ARM（s5pv210）使用V4L2 USB相机图像捕获，图像识别](http://www.codeforge.cn/article/303362/)   

## Debug  
[Linux下CodeBlocks远程调试ARM程序环境搭建](https://blog.csdn.net/wcl719236538/article/details/52314231)  

## GHOTO
[windows+Ubuntu双系统引导修复（终极版）](https://blog.csdn.net/lhj_168/article/details/75212421)  
[你必须安装libtool和autopoint：](https://sourceforge.net/p/gphoto/mailman/message/11167978/)  

sudo apt-get install autoreconf

sudo apt-get update
sudo apt-get install libtool autopoint

如果你不能只用你的安装libpopt-dev或popt-devel包
系统的标准包机制，手动安装到一些前缀
然后设置

   POPT_CFLAGS = 3D-I $ {PREFIX} /包括
   POPT_LIBS = 3D“-L $ {prefix} / lib -lpopt”

在运行gphoto2的配置之前。

但是，只需从您的安装适当的popt开发包
分配是推荐的方式。

[linux下USB数据包分析(usbmon + wireshark)](http://www.lnsign.com/2018/03/06/usb-packet-capture-usbmon-wireshark/)  
