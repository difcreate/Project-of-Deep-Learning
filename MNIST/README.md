运行该文件需要翻墙才能自动获取MNIST数据集，不然无法运行。

运行语句：

```python
python mnist.py
```

可以通过Tensorboard查看训练状态

```python
tensorboard --logdir=./MNIST_LOG --port=8008
```