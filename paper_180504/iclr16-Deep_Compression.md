## Deep Compression: Compressing Deep Neural Networks With Pruning, Trained Quantization and Huffman Coding
* Paper: https://arxiv.org/abs/1510.00149
#### 深度神经网络压缩
* 问题
	1. 神经网络参数冗余;
	2. 存储空间大；运算速度慢（读取模型速度+运算速度）;
	3. 无法应用到嵌入式;
* 解决方案
	1. 剪枝。减掉多余连接;
	2. 参数量化。不同连接共享权重;
	3. 哈夫曼编码。权重的分布。
