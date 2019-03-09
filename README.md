# 项目 : 创建用户细分
该项目属于优达学城机器学习纳米学位”非监督学习“项目，数据集是葡萄牙里斯本的某批发商所收集的客户产品开支数据（共440个样本，6个特征）。通过非监督学习的方法(PCA,KMeans及高斯混合模型等)发现数据中隐藏的客户细分信息，帮助批发商根据不同的客户群体实行针对性的服务标准，最大程度的减少成本增大收益。

### 安装

这个项目要求使用 **Python 3** 并且需要安装下面这些python包：

- [NumPy](http：//www.numpy.org/)
- [Pandas](http：//pandas.pydata.org)
- [scikit-learn](http：//scikit-learn.org/stable/)

推荐安装 [Anaconda](https：//www.continuum.io/downloads), 这是一个已经打包好的python发行版，它包含了我们这个项目需要的所有的库和软件。

### 代码

代码包含在`customer_segments.ipynb`这个notebook文件中。还会用到`visuals.py`和名为`cluster.csv`的数据文件来完成这个项目。 
注：该项目中部分初始代码以及`visuals.py`文件由优达课程提供。其它部分自行完成。


### 运行

在命令行中，确保当前目录为 `customer_segments.ipynb` 文件夹的最顶层（目录包含本 README 文件），运行下列命令：

```jupyter notebook customer_segments.ipynb```

​这会启动 Jupyter Notebook 并把项目文件打开在你的浏览器中。

## 数据

​这个项目的数据包含在 `cluster.csv` 文件中。你能在[UCI 机器学习信息库](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers)页面中找到更多信息。
