## Udacity ND101 - Deep Learning Foundation Nanodegree

本文档的素材来自于 Udacity 纳米学位《机器学习基础》。相关环境已在 RussellCloud 配置完善。帮助用户摆脱繁琐的环境配置，真正专注于课程的学习。通过 RussellCloud 准备的`jupyter notebook`，即刻开启深度学习之旅。

这些代码从官方的课程链接获取，仅保留了对应的必要文件。数据集也以上传至 RussellCloud 数据集。

## 项目二：第一个神经网络

在本项目中，你将学会对 CIFAR-10 数据集进行分类。该数据集包含了飞机、狗、猫以及其它物体。需要对这些图片进行处理，训练一个卷积网络进行分类。图片需要正则化、标签需要进行 one-hot 编码。

通过以下步骤生成你的专属 `jupyter notebook` 并运行第二个项目：


### 1. 创建一个 RussellCloud 账户

- 登录 RussellCloud
- 通过以下两步，安装 Russell客户端:

```
$ pip install -U russell-cli

$ russell login
```

### 2. Clone 项目至本地

```
$ git clone https://github.com/RussellCloud/deep-learning.git
$ cd deep-learning/image-classification
```


### 3. 在 RussellCloud 上创建项目

在 RussellCLoud 上创建名为`image-classification`的项目，环境选择`keras`，然后在本地使用如下指令绑定它：

```
$ russell init image-classification
```
### 4. 通过 `jupyter notebook` 运行项目

- `--env` 标志，指定项目的运行环境。本项目需要 Tensorflow 1.2.0 + Keras 2.0.6 + Python 3.5。
- `--data` 标志，指定数据集ID。
- `--mode` 标志，是否弹出 `jupyter notebook`。
- `--gpu` 标志，可选。如果确定代码能够直接运行不用调试，则可以开启GPU加速。否则，建议先用CPU调通代码。

```
russell run \
  --env keras \
  --data fd3a1fa0ffd045958c663e4f8c2fc36e:data \
  --mode jupyter \
  --gpu

```
任务一旦开启，`jupyter notebook`将会在你的浏览器打开。接下来就可以你的操作啦～

## 更多关于 RussellCloud 平台
- 注意，在 RussellCloud 端的改动不会影响本地文件。若想更改本地文件，可将网页端的文件下载下来覆盖。
- 如果需要帮助，可查看我们的[文档](http://docs.russellcloud.com)，或是参与[论坛](http://forum.russellcloud.com/)讨论。

