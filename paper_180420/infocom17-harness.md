## Harnessing Hardware Defects for Improving Wireless Link Performance: Measurements and Applications
* Paper: https://ieeexplore.ieee.org/abstract/document/8056967/
#### 利用硬件设计缺陷，降低 802.11 协议传输 Error Rate
* 问题
由于硬件缺陷，802.11协议数据传输存在特定的 Error Pattern。
* 解决方案
1. 设计补偿电路，确定 Error Pattern 存在的原因是低通滤波器缺陷。低通滤波器导致能量损耗，边缘频率载波能量低，有较高的Error Rate；  
2. 重新排列数据包顺序，在边缘频率载波发送相对不会影响其他数据的数据，降低数据传输Error Rate。