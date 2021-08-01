<font size=10>**NER（中文实体命名识别）**</font>



**光健字: 中文命名实体识别 NER  BILSTM CRF IDCNN BERT**



**摘要：对中文命名实体识别一直处于知道却未曾真正实践过的状态，此次主要是想了解和实践一些主流的中文命名实体识别的神经网络算法。通过对网上博客的阅读了解，中文命名实体识别比较主流的方法是BILSTM+CRF、IDCNN+CRF、BERT+BILSTM+CRF这几种神经网络算法，这个demo也用Keras实现了这几个算法，并且采用几个比较通用的数据集进行训练测试。这个demo是以了解和学习为目的的，所以未得出任何结论**



**注意：由于算力和时间的问题，对神经网络的参数未进行太多调试，所以模型现在的参数并不是最佳参数**



# 主要库的版本

本项目是基于keras（Using TensorFlow backend）以下是主要库的版本

- python = 3.6.8



- keras == 2.2.4
- keras_contrib == 0.0.2
- keras_bert == 0.80.0
- tensorflow == 1.14.0



