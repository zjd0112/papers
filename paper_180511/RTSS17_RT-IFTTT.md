## RT-IFTTT: Real-Time IoT Framework with Trigger Condition-aware Flexible Polling Intervals
* Paper: http://corelab.postech.ac.kr/Pubs/rtss17_rt-ifttt.pdf
#### Trigger Condition aware 的 IFTTT规则
* 问题
	1. IFTTT，server 读传感器数据时间间隔是固定的;
	2. 间隔过长，实时性不能保证，间隔过短，sensor能量消耗大;
* 解决方案
	1. 预测。根据历史数据，预测之后的数据会达到 trigger 触发条件的概率;
	2. 根据预测值，系统选取合适的时间间隔;
