## 基于Tensorflow，OpenCV
## 使用MNIST数据集训练卷积神经网络，用于手写数字识别

#### ocr.py
一个单层的神经网络，使用MNIST训练，识别准确率较低

#### cnn_ocr.py
两层的卷积神经网络，使用MNIST训练，识别准确率较高；
但是如果写的较为随意的，还是会出现分类错误的情况，可能是图像预处理的问题