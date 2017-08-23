# Evaluation of CNN
刚刚，卓龙已经介绍了CNN（Convolutional Neural Network）,接下来，我会介绍三个CNN的重要应用，他们也在不同程度上推动了现代机器学习的发展。
## AlexNet
* 在ILSVRC2012年时，出现了8层的网络——AlexNet，降低了10%的错误率。
* 2012年，Alex 提出了深度卷积神经网络模型AlexNet，AlexNet以显著的优势赢得了竞争激烈的ILSVRC2012比赛。
* AlexNet使用了GPU进行运算加速，作者开源了他们在GPU上训练卷积神经网络的CUDA代码。
* AlexNet可以说是神经网络在低谷期后的第一次发声，确立了深度学习（深度卷积网络）在计算机视觉的统治地位，同时也推动了深度学习在语音识别、自然语言处理、强化学习等领域的拓展。
* 把CNN的基本原理应用到了很深很宽的网络中。
## ResNet
* Resnet在ILSVRC 和COCO 2015上的表现在五个主要任务轨迹中都获得了第一名的成绩
* 一个能够用来训练“非常深”的深度网络又十分简洁的框架
* ILSVRC2015，我们的ResNet将层级提到了152层，将错误率降到了3.57。
* 深度残差网络(ResNets)具有较低的训练误差和测试误差。
* 与VGG-16/19相比，该模型具有较低的时间复杂度。
## Recurrent Neural Networks