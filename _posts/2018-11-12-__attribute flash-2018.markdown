---
layout:     post                    # 使用的布局（不需要改）
title:      STM32学习笔记之__attribute__ ((at())绝对定位分析    # 标题 
subtitle:    第一篇                  #副标题
date:       2018-09-25              # 时间
author:     BY Edlward              # 作者
header-img: img/post-bg-2015.jpg    #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - STM32
---

[STM32学习笔记之__attribute__ ((at())绝对定位分析](https://blog.csdn.net/sinat_23338865/article/details/51960362)  
学习STM32也会遇到这样的绝对定位的问题如下：

uint8_t   UART_RX_BUF[1024]   __attribute__ ((at(0X20001000)));   //就是将串口接收的数据定位到RAM中起始地址为0X20001000；

绝对定位要么定位到flash、要么定位到RAM,这里我们将定位在flash进行说明。

MDK如何实现将数据存储到FLASH指定地址？

      我们在烧录数据的时候，一般是从0x08000000开始按照顺序烧录到flash里面的，如何让数据能够定义到绝对地址如0800F000,就必须保证文件内数据也是存储在该地址，为了实现这个目的，MDK在生成文件时会填充0x00字段，从而确保能够将数据定义到
--------------------- 
作者：偏执灬 
来源：CSDN 
原文：https://blog.csdn.net/sinat_23338865/article/details/51960362 
版权声明：本文为博主原创文章，转载请附上博文链接！
