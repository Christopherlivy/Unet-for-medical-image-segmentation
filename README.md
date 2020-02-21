# Unet-for-medical-image-segmentation

首先将自己的数据集中要训练的label和mask放入deform下的对应文件夹下，按数字顺序命名 如1.tf

将测试集图片放入test中，命名格式相同

运行data.py生成数据，运行unet.py开始训练，生成预测在results中

注意：
1.文件夹格式请不要改变，不然请在代码中更改与文件路径有关的代码
2.命名格式改变请改变sort函数和代码路径等
3.其他改变具体请先阅读博客，地址：https://blog.csdn.net/Yanhaoming1999/article/details/104430098
