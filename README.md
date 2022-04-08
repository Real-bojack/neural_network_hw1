## 代码框架
```
dataset/
    4个gz压缩文件为mnist数据集
    mnist.py 数据集的相关操作
    mnist.pkl 保存的数据集的参数，用于模型的读取

util.py 辅助文件
multi_layer_net.py 神经网络模型文件
hyperparameter_search.py 参数查找文件
two_layers_train.py 神经网络训练文件，可视化训练和测试的loss曲线，测试的accuracy曲线
visualize_parameters.py 可视化模型参数的文件
params.pkl 保存的模型参数
```
## 如何运行
```
直接运行hyperparameter_search.py 进行参数查找
选择从上一步骤找到的最优参数，用于神经网络的训练，运行two_layers_train.py
上一步训练得到的模型会保存在params.pkl
运行visualize_parameters.py 可视化模型的参数
```
