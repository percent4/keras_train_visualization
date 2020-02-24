&emsp;&emsp;本项目用于实时展示Keras模型训练过程中的实施可视化。

&emsp;&emsp;本项目借助别人已经开发的代码，进行网页端展示。参考项目为hualos，网址为：[https://github.com/fchollet/hualos](https://github.com/fchollet/hualos) 。原项目对于新版本的Python2的模块有些不兼容，现已修改，同时前端网页的展示文字已修改。

### 准备工具

Python2:

- Flask==1.0.2
- gevent==1.4.0

Python3:

- tensorflow==1.13.1
- Keras==2.2.4
- pandas==0.23.4
- numpy==1.16.2
- scikit-learn==0.21.3

### 运行步骤：

1. 切换至hualos文件夹，运行api.py脚本，命令为:

```bash
python api.py
```

2. 在浏览器中打开网址： http://localhost:9000

3. 运行脚本model_train.py，命令为:

```
python3 model_train.py
```

### 运行效果图

![](https://github.com/percent4/keras_train_visualization/blob/master/result.png)