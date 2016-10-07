# 利用Scikit Learn对秒级股票数据进行建模预测

这里我们学习Scikit Learn的安装和基本操作，并且尝试通过Scikit Learn对秒
级股票价格数据进行预测。

## 下载本章实例程序

下载本章节实例程序和数据，只需执行下面操作：

```shell
git clone https://github.com/real-time-machine-learning/2-scikit-learn-intro
```

## 安装配置软件环境

我们假设读者在Ubuntu或者Mac环境下进行学习。下面的步骤可以供Windows用户
参考，但可能需要稍作修改。

### 安装Python3 

在Ubuntu 下面安装Python 3，只需执行下面操作：
```shell
sudo apt-get install python3 python3-pip python3-dev build-essential 
```
在Mac下利用Homebrew 安装Python 3，只需执行下面操作：
```shell
brew install python3
```
Windows用户……安装一下Ubuntu好吗？

### 安装Scikit Learn

这里我们通过Python的Pip配置文件的方法安装Scikit Learn。在后面的Docker学
习中，我们可以看到这样的配置方法非常利于自动化Docker操作。

```shell
sudo pip3 install -r requirements.txt
```

如果一切顺利，上面操作完成以后，我们可以启动Python3并且调用Pandas
```shell
python3 
>>> import sklearn 
```

## Pandas基本操作

下面我们将利用`example.py`中的操作介绍Scikit Learn的基本模块。


--- 
《实时机器学习实战》 彭河森、汪涵

