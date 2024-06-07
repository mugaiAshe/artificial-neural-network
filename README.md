# artificial-neural-network
Use artificial neural networks to solve some classic problems.

1.猫咪分类问题：

对于paddle的代码，首先把data目录下的文件（ipynb文件、两个压缩包zip文件，ResNet50和ViT的预训练模型文件）传入paddle项目的work工作区内，需要手动解压一下数据和模型文件的压缩包cat_12_train.zip（训练数据文件）和work.zip（保存的最优模型文件），然后按照说明运行ipynb文件即可。

对于pytorch代码，则需要：ipynb文件、cat_12_train.zip（训练数据文件）、保存的最优模型文件best_model_train.pth。手动解压一下数据压缩包，然后按照说明运行ipynb文件即可。

paddle版本2.6.0，其他库以及pytorch的代码都是缺什么库装什么库。（pip安装即可）


2.新闻标题分类：

对于paddle的代码，将目录下所有文件放入paddle项目的根目录中，然后运行ipynb文件即可。

对于pytorch代码，则需要：ipynb文件、data文件。

paddle版本2.1.0

paddlenlp版本2.0.1（这个安装已经在代码中写出）

其他库以及pytorch的代码都是缺什么库装什么库。（pip安装即可）

pytorch_GAN.ipynb会对原数据进行修改，应该最后运行。



3.中英文翻译：运行ipynb文件即可。

paddle版本2.0.2

需要的库环境和版本在代码中有说明，运行即可。
