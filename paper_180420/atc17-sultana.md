## Emu: Rapid Prototyping of Networking Services
* Paper: https://www.usenix.org/system/files/conference/atc17/atc17-sultana.pdf
#### 基于 FPGA 的网络应用快速编程
* 已有方法
HLS，将高级语言(C++/C#)转化成硬件描述语言(Verilog/VHDL)。
* 问题
	1. 缺少库的支持；
	2. 缺少调试支持；
* 解决方案
基于已有的Kiwi工具，自己写了一套网络编程库，集成到Kiwi中。