**Note**:This document store the process of LeNet Neural Network model working on MNIST dataset.

# LeNet手写数字识别 (MNIST)

**实验环境:**  
* Pytorch 1.1.0 
* Anaconda 1.9.0
* Ubuntu 18.0.4 LTS

**Note:**  
> It is highly recommended that you training or testing your AI models in Ubuntu system. You will find it very convenient to train artificial intelligence models in the system.

-----

## LeNet网络结构：

![](https://img-blog.csdn.net/20180426101343001?watermark/2/text/Ly9ibG9nLmNzZG4ubmV0L3N1bnFpYW5kZTg4/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

### 网络参数：


|layer name|kernel size|output size|
|:-------------:|:-------------:|:-------------:|
|     输入层   |	\  | 32x32 |
| 卷积层1	| 5x5 | 	6x28x28 |
| MaxPool1	| 2x2, stride=2	 | 6x14x14|
| 卷积层2 |	5x5 |	16x10x10 |
| MaxPool2  |	2x2, stride=2 |	16x5x5| 
| 全连接层1 |	16x5x5 |	120 |
| 全连接层2 |	120 |	84 |
| 输出层 |	84 |	10 |

--------------------- 