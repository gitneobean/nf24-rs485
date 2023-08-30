# nf24-rs485
rs485与rf2.4协议转换器

说明:
本项目的主要功能是将有线RS485数据通过RF24发送出去或将RS24接收到的数据转发到RS485上
本项目包括 电路设计图、PCB以及mcu的C代码实现

目录说明：
kicad：基于kicad设计的电路原理图和PCB（mcu为cx32l003）
iar：基于iar编写的程序源代码
python：基于python编写的转换器配置工具
release：pcb制造文件和编译好的二进制烧录文件
