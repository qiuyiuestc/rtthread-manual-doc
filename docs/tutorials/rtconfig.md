#  RT-Thread配置选项说明 #

RT-Thread包含一个rtconfig.h文件，该文件包含一系列宏定义，用来裁剪RT-Thread，配置内核和组件参数。RT-Thread推出了ENV工具，提供了类似Linux内核裁剪配置的图形化工具，因此一般不需要手动修改rtconfig.h文件。

## 内核部分 ##

| 名称 | 描述 |
| - | - |
| RT_NAME_MAX | 线程名字最大长度  |
| RT_ALIGN_SIZE | 字节对齐，对于ARM，为4字节对齐 |                                                         
|RT_THREAD_PRIORITY_MAX |最小线程优先级值|
|RT_TICK_PER_SECOND |每秒tick数，一般为1000|
|RT_DEBUG|debug选项|
|RT_USING_OVERFLOW_CHECK|栈溢出检测|
|RT_DEBUG_INIT|初始化debug| 
|RT_USING_HOOK|使能钩子函数|
|IDLE_THREAD_STACK_SIZE|空闲线程栈大小|
|RT_USING_SEMAPHORE|使能信号量|
|RT_USING_MUTEX|使能互斥锁|
|RT_USING_EVENT|使能事件|
|RT_USING_MAILBOX|使能邮箱|
|RT_USING_MESSAGEQUEUE|使能消息队列|
|RT_USING_MEMPOOL|使能内存池|
|RT_USING_MEMHEAP|使能内存堆|
|RT_USING_HEAP|使能堆|
|RT_USING_SMALL_MEM|使能小内存管理策略|
|RT_USING_DEVICE|使能设备|
|RT_USING_CONSOLE|使能终端|
|RT_CONSOLEBUF_SIZE|终端缓存大小| 
|RT_CONSOLE_DEVICE_NAME|终端设备名字| 
|RT_USING_COMPONENTS_INIT|使能组件初始化|
|RT_USING_FINSH|使能finsh组件|
|FINSH_USING_HISTORY|使能finsh历史记录|
|FINSH_USING_SYMTAB|使能tab键补全命令|
|FINSH_USING_DESCRIPTION|使能命令描述|
|FINSH_THREAD_PRIORITY|fish线程优先级|
|FINSH_THREAD_STACK_SIZE| fish线程栈大小|
|FINSH_CMD_SIZE|fish命令字长度 |
|RT_USING_DEVICE_IPC|使能设备通信|
|RT_USING_SERIAL|使能串口|
|RT_USING_EXT_SDRAM|使能外部SDRAM|
|RT_USING_UART1|使用串口1|
|RT_USING_UART2|使用串口2|
|RT_USING_UART3|使用串口3|
|RT_USING_SPI5|使用SPI5|
|RT_RTC_NAME |RTC名字|

