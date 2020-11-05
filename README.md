# 作业说明

本次作业使用迁移学习训练花朵分类数据集，从DJL ModelZoo里选取预训练模型来训练。

数据集官网：[102 Category Flower Dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/)

数据下载地址: https://d2l-java-resources.s3.amazonaws.com/flower_dataset.zip

1. 本次作业建议使用GPU训练，欢迎使用AWS EC2的GPU实例
  - 使用AWS EC2 运行notebook方法: https://zh.d2l.ai/chapter_appendix/aws.html
2. 安装Jupyter Notebook和IjavaKernel
  - 安装步骤： https://docs.djl.ai/jupyter/index.html
3. 启动Jupyter Notebook, 根据 [homework_3.ipynb](./homework_3.ipynb)的提示，完成注释部分，训练模型
4. 加分项

- 使用不同的预训练模型训练，参考ModelZoo模型：https://docs.djl.ai/docs/model-zoo.html
- 使用不同的超参数，调整模型效果： 参考资料：https://docs.djl.ai/examples/docs/train_cifar10_resnet.html#learning-rate-schedule
  - 更换学习率，LR Tracker
  - 更换Optimizer， 例如Adam
- 用多GPU加速学习, 参考资料：https://docs.djl.ai/examples/docs/train_cifar10_resnet.html#train-using-multiple-gpus

## 提交方法： 
把代码 checkin 到一个 Github 的 repo 里/或打包 zip，然后将 zip/GitHub repo url 发送
到：deepjavalibrary@gmail.com。
