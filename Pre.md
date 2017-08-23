# Evaluation of CNN
My fellow ,Zhuo long ,has introduce CNN to you ,now I’m going to talk about 3 important network ,based on CNN
## AlexNet
* First,The 8-layers Net---AlexNet,It Came out from ILSVRC（ImageNet的图像识别竞赛） 2012 and win the frist place,because,it reduce the error rate to 16.4%,Which is a huge progress.
* It is very important because it proved that CNN can be use in a deep,wide Network and is very powerful in Computer Vision. it also advance the usage of CNN in Speech Recognition,Nature Language process and many other field.It use GPU to make Calculate faster,which has become popular today.
## ResNet
* Next one is ResNet,ResNet won the first place in both ILSVRC 2015 and COCO 2015（也是一个图像识别比赛）,In ILSVRC 2015,the MSRA team use a 152-layers ResNet and reduce the error rate to 3.57%.It is a simple and clear framework to train a very deep network.it have lower training error , lower test error and also ,lower time complexity（时间复杂度）.
* This success advance the Revolution of Network Depth because if you just simple stacking layers ,you will get higher training error and test error ,but in this solution,you can actually benefit from the increased number of the layer. 
## Recurrent Neural Networks
* Now,We had Introduced two Network ,their main tesk is Computer Vision .Last one is Long Short-Term Memory Networks . It is based on RNN（递归神经网络）,but it’s better than RNN,Because RNN have gradient Vanishing/Exploding problem ,but LSTM fixed it by using Memory Cell instead of normal RNN cell .So ,LSTM make RNN more practical .It has being used on many tesks ,Such as Handwriting recognition ,Semantic analysis and etc.It become popular because you can get a very good result by a 2 or 3-layers LSTM.
