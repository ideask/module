# module
#2017年4月5日：
#1.将设备驱动改写为字符设备，为设备驱动增加读写功能。
#2.读取内核调试信息，每次读1024个字符，然后对每行进行排序{序号}：，将不完整的行优先提取出来并且打印。

