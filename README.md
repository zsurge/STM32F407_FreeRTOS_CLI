# STM32F407_FreeRTOS_CLI
STM32F407 + FreeRTOS+CLI
基于正点原子探索者开发板，移植的一个简单的FreeRTOS+CLI
目前程序有一点小问题，在FreeRTOS文件夹下port.c中vPortValidateInterruptPriority这个函数需要添加一些延时，要不串口显示出来的数据不全。若是那位大侠知道原因，做出修改，希望能告诉我，拜谢！
