初见
=====================

.. contents:: 本文目录

从硬件说起
------------------------

荔枝派Nano（下面简称Nano）是一款精致迷你的 Arm9 核心板/开发板，可用于初学者学习linux或者商用于产品开发。 Nano 在与SD卡相当的尺寸上（25.4*33mm）提供了丰富的外设（LCD,UART,SPI,I2C,PWM,SDIO,KEYADC...）和较为强劲的性能（ 24M~408MHz, 32MB DDR ）。

Nano 延续并发展了Zero精巧的PCB设计，使得开发和使用非常方便：

1. 2.54mm排针直插面包板
#. 直插40P RGB LCD
#. 使用OTG口进行供电和数据传输(虚拟串口，更新固件等)
#. 可配合使用使用堆叠式的WiFi 模块联网
#. 直接贴片

Nano 实物图
~~~~~~~~~~~~~~~~~~~~~~~~

Nano 硬件参数
~~~~~~~~~~~~~~~~~~~~~~~~

Nano 手册资料
~~~~~~~~~~~~~~~~~~~~~~~~

国内下载： 

    百度云盘： https://pan.baidu.com/s/1rajyI3E

    原理图：http://odfef978i.bkt.clouddn.com/Lichee_nano.pdf

    RT-Thread SDK : https://github.com/RT-Thread/rt-thread


Nano 管教定义
~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: http://odfef978i.bkt.clouddn.com/Pin%20Map.png
   :width: 500px
   :align: center
  
   Pin Map

说点软的
------------------------

荔枝派 Nano支持多个系统，可自由使用Linux、RT-Thread、Xboot或裸机等进行操作。

荔枝派 Nano支持从SPI Flash中启动系统

用到哪去
------------------------

荔枝派Nano 的目标应用场景是：

- 使用较复杂的通信接口和协议的物联网应用
- 需要较美观，复杂逻辑的人机交互界面的应用
- 需要较多运算(相对于常用MCU)的应用场景
- 需要使用RTT、linux下的开源软件包进行快速开发的场景
- 高端极客玩家，在体积、性能、易用性 上取得平衡。
- 入门级玩家，软件工程师，使用熟悉的语言进行硬件diy。

荔枝派Nano 可以做的，比如还有：

