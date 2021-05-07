# jvm上篇尚硅谷

### 第一章 VM与Java体系结构

##### 1，跨平台

![jvm-1跨平台](D:\学习Java\linux\csdn\jvm-1跨平台.png)

不同的计算机语言都能够用Java虚拟机来解释执行程序翻译为机器指令

##### 2，特点

- 自动内存管理
- 一次编译、到处运行
- 自动拉机回收功能

##### 3，所在的位置

![jvm-1.位置](D:\学习Java\linux\csdn\jvm-1.位置.png)

##### 4，整体的结构

![jvm-1整体的架构](D:\学习Java\linux\csdn\jvm-1整体的架构.jpg)

##### 5,程序执行的流程

![jvm-1流程](D:\学习Java\linux\csdn\jvm-1流程.jpg)

##### 6，架构的类型

编译器一般地来说有两种架构类型

- Java采用的为于栈的架构

不要硬件的支持 移植性好些 

- 令一种则采用的为寄存器的架构

这种类型的架构依赖硬件 直接与硬件进行交互 因此运行的效率很快

![jvm-1架构](D:\学习Java\linux\csdn\jvm-1架构.jpg)

##### 7，生命的周期

![jvm-1周期](D:\学习Java\linux\csdn\jvm-1周期.jpg)



### 第二章类加载子系统

##### 1，内存结构概述

##### 2，类加载过程

![jvm-1过程](D:\学习Java\linux\csdn\jvm-1过程.jpg)

这里主要有三个过程

- loding

首先由引导类、扩展类、系统类三种类加载器来进行将类loading进来

通常为以流的形式

- linking

![jvm-1linking](D:\学习Java\linux\csdn\jvm-1linking.jpg)



- initialization

![jvm-1initialization](D:\学习Java\linux\csdn\jvm-1initialization.jpg)



##### 3，加载器的类型

主要包含了这三种

- 引导类

![jvm-1引导类](D:\学习Java\linux\csdn\jvm-1引导类.jpg)