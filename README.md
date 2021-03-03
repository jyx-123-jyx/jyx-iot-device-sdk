# jyx-iot-device-sdk
This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.         For more information, please check Tuya Developer Website.

一、方案标题 
==
现代化农业智能灌溉系统 

二、功能实现的基本构想
==
本次设计，以正点原子stm32f103精英版为主控单片机我们可以通过土壤湿度检测模块检测到一个模拟信号，并通过内部的AD转换器将其转换为数字信号，也就是的土壤湿度值。根据当前的土壤湿度值，设置不同的灌溉周期，。在需要灌溉的时候就给继电器一个使能信号，打开提前预制好的水泵开始浇水，在不需要灌溉的时候同样给继电器一个停止的信号。设备通过WIFI模块连接至涂鸦IOT平台，通过http协议进行交互，将本地的土壤湿度的实时数据发送到云端，通过网页端进行土壤环境的基本监测及控制
ps：如果能力达到的话，借助LED灯光代替太阳光成为植物生长发育环境。根据农产品的不同阶段智能调节光量、光质。根据农作物生理时段的不同调节光照波长，缩短农作物的生长周期

三、方案应用场景
==
现代化农场的瓜果灌溉及花卉培育 

四、开发计划 
==
3月25前完成. 
1）3月7前准备物料 
2）3月10-15日嵌入式开发、云开发 
3）3月15日前整体调试。
