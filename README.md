# 狗狗图像识别项目
[//]: # (Image References)

[image1]: ./images/dog.png "需要识别的狗狗图像1"
[image2]: ./images/dog2.png "需要识别的狗狗图像2"


## 项目概述

欢迎来到深度学习试学班的最后一个项目！在这一项目中，你将学习建立一个神经网络，该网络可以帮助你来识别狗狗。给你一个狗狗的图像，你的算法将会识别并评估这个图像是不是狗狗，并显示图像是狗狗的概率。

我们的目标是，当你完成这一项目时，你将可以理解，神经网络中的正向、反向传播、交叉熵的反馈等。你将通过调整神经网络中的超参数，来把最终的预测结果变得更好。


## 项目指南

### 步骤

1. 克隆存储库并打开下载的文件夹。

 ```	
git clone https://github.com/udacity/cn-deep-learning.git
cd cn-deep-learning/dog-project
```

2. 安装必要的 Python 依赖包


	对于 __Mac/OSX__：
	
	```bash
	conda env create -f requirements/dog-mac.yml
	source activate dog-project
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	对于 __Windows__：
	
	```bash
	conda env create -f requirements/dog-windows.yml
	activate dog-project
	set KERAS_BACKEND=tensorflow
	python -c "from keras import backend"
	```
3. 打开 notebook

 ```
jupyter notebook dog_app.ipynb
```

__注意：__ 我们虽然已经实现了一些代码，让你更快地开始工作，你仍需要实现额外的功能，以回答 notebook 中所有的问题。
__除非有要求，否则不要修改任何已经包含的代码。__

## 项目评审

你的项目将会由优达学城的审阅者依据次项目的[评审标准](https://review.udacity.com/#!/rubrics/1080/view)进行审阅。请仔细阅读，并在提交之前自我评估你的项目。你必须通过了规则中的所有要求，才会审核通过。

## 项目提交

当你准备好提交你的项目时，将下列文件整理并压缩成一个文件，以便上传。

- 代码完整可运行的文件 `dog_detection.ipynb`，所有的代码块都要执行并展示结果，并要求回答所有问题
- 将你的 notebook 导出为 HTML 或 PDF 格式，并以 `report.html` 或是 `report.pdf` 命名

此外，你也可以通过 GitHub 连接提交项目。
