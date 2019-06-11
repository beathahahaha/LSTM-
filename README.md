# LSTM-
LSTM长短期记忆模型预测股票涨跌

运行环境：
windows10
jupyter notebook
python 3.6
tensorflow 1.13.1 (cpu版本)
numpy 1.16.4

ipynb文件在jupyter notebook下都可以直接运行

2018.12.10LSTM实现股价预测(可视化，有dnn对比试验).ipynb   
运用前10天(before=10)股票每日的open，close，high，low(开盘价，收盘价，最高价，最低价)去预测下一天该股票的收盘价，最后预测出的是具体的数值形式，并且有可视化

2018.12.24LSTM实现股价预测(二，重点：标签分类).ipynb
类似上个文件，不同的是预测的是下一天该股票的涨跌，是一个二分类问题，评测指标采用准确率和f1值
