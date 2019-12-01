# -  基于RT-Thread的空气质量分析仪，是实战营的一个小项目，通过这个项目进一步了解RT-Threda的魅力，也希学到自己的东西。

本次项将带你学习：
1、不同bsp的移植和灯光系统：
     1.1、 主要介绍在这里我介绍两种方法：
直接从 CubeMX 中导入该软件包。
在官网下载rtthreadd源码，整理出自己的bsp。
         1.2、灯光系统实现灯的开关，闪烁。
         1.3、按键扫描
2、空气质量采集部分
          2.1、采集PM2.5
          2.2、使用DHT1采集空气的温湿度
          2.3、有害气体的采集（选用）
3、数据处理、格式化打印部分：
3.1、实现按键选择指定传感器的采集打印
3.2、实现异步日志（熟悉 IPC：邮箱的使用）
3.3、系统跑起来（熟悉 IPC：事件集的使用）
4、发挥部分（这里是实现云平台）
       4.1、通过 esp8266 wifi 模块将接收节点的数据传输至
OneNet 云，实现远程监控
