# Mid-Term Assignment for *Fundamentals and Applications of Large Models*

这个项目只实现了Transformer的基本架构，没有针对特定数据集进行实验。可以使用以下命令安装依赖并运行代码：

```
$ conda create -n transformer python=3.11
$ conda activate transformer
$ conda install numpy==1.23.5 pytorch==2.3.0 cpuonly -c pytorch
$ python src/Transformer.py
```

运行程序后，控制台显示输出结果的维度：

```
torch.Size([16, 100, 26])
```
