AutoLights
===============
Do you have the moment that you discover toilet lights not turned off after you go to bed? Or have to find the lights in the dark first when changing baby diapers in the middle of night? These simple tasks should be done automatically. This project try to use mechine learning algorithm to control the lights after learning user hibits. In design, poeple can use the light asusual, the light learns user hibits in silent, after a while it can turn on or off on it's own when environment matches.

Hardware feature
----------------
* STM32F103C8T6 MCU              
* Light sensor             
* Sound sensor(volume only)              
* one relay(ON/OFF only)                
* three wire UART port                  
* three wire SWD port                   

Progress
----------------
20160301：Basic architecture of software and hardware in mind. Use simple algorithm KNN.

Development blog
---------------
<http://lsgeek.blogspot.com>, TODO, no article yet.

自动电灯
===============
你是否遇到过已经钻进被窝却发现厕所灯还没有关？你是否遇到过晚上给宝宝换尿不湿还要先摸黑开灯？这些简单的工作，应该能够实现自动控制。本项目尝试使用机器学习算法学习用户使用习惯，从而实现自动控制电灯的开关。设计使用方法：用户按照之前的习惯使用电灯，电灯默默学习用户的使用习惯，之后在恰当的时刻实现自动执行开关操作。

硬件资源
---------------
* STM32F103C8T6                
* 亮度传感器              
* 声音传感器（仅检测音量）           
* 一路继电器（仅控制开关）           
* 三线串口            
* 三线SWD                 

当前进度
---------------
20160301：设备软硬件架构有大致的思路，算法选择最简单的KNN。

开发博客
---------------
<http://blog.sina.com.cn/lgeek>  TODO, 暂时还没有文章
