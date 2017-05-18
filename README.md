# 用Python做贝叶斯分析

本书代码部分使用的是Python3.5以上的版本，因此建议你使用Python3的最新版，尽管本书的大部分代码都能在更早的版本上运行（包括Python2.7，不过可能需要稍微修改下）。

安装Python和Python库最简单的方法是使用Anaconda（一个用于科学计算的软件），你可以从这里了解和下载Anaconda [https://www.continuum.io/downloads](https://www.continuum.io/downloads)。在安装好Anaconda之后，可以使用`conda install 库的名称`来安装相关的Python库。

本书会用到以下Python库：

- Ipython 5.0
- NumPy 1.11.1
- SciPy 0.18.1
- Pandas 0.18.1
- Matplotlib 1.5.3
- Seaborn 0.7.1
- PyMC3 3.1rc3

注意：

1. 如果你已经安装了Python2.7版本的Anaconda，可以通过执行`conda create -n py3 python=3 anaconda`增加一个py3的环境，然后运行`source activate py3`切换过去，运行完代码之后，执行`source deactivate`切回去。

2. 通过`pip install pymc3`安装的PyMC3版本会比较旧，建议直接运行`pip install git+https://github.com/pymc-devs/pymc3`安装。

## 相关书籍

- [贝叶斯方法：概率编程与贝叶斯推断](http://www.epubit.com.cn/book/details/4274)
- [概率编程实战](http://www.epubit.com.cn/book/details/4366)
- [Statistical Rethinking](https://book.douban.com/subject/26607925/)
- [Doing Bayesian Data Analysis, Second Edition](https://book.douban.com/subject/26206378/)
- [Bayesian Data Analysis, Third Edition](https://book.douban.com/subject/17380364/)

## 建议和反馈

请直接提[issue](https://github.com/findmyway/Bayesian-Analysis-with-Python/issues)。
