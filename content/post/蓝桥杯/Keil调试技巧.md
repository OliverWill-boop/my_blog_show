---
title: keil调试技巧
description: 学习笔记
date: 2026-04-03
slug: keil调试技巧
categories:
    - 蓝桥杯
tags:
    - 蓝桥杯
---

# keil调试

![](https://raw.githubusercontent.com/OliverWill-boop/my_blog_img/main/image-20260402230907460.png)

- 记得要先把板子插上去
- 按一下板子上的下载按键
- 其实本质也是一种烧录，烧录的是isp自带的程序，相当于给我们提供了一层接口，让我们能够在keil上对它进行仿真

![image-20260402231331470](https://raw.githubusercontent.com/OliverWill-boop/my_blog_img/main/image-20260402231331470.png)

- 这之后会提示我们重复给单片机上电，我们就需要把板子拔掉，再重新插上
- 然后点击放大镜就可以进入调试状态
- 只有全局变量才能被监视
- 黄色箭头是程序当前位置，蓝色箭头是光标所在

> 值在哪个地方被改变，就在哪个地方打断点

> 可以通过打两个断点的方式找到程序进入了哪个判断，如果不管怎么调整输入，都是只进入那一个判断分支，那就说明判断条件有问题

> 另外，断点和串口是不能同时使用的，这是蓝桥杯单片机板子硬件的问题