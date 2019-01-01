# MLP

load_train只是从原先数据提出输入和输出

主要预处理在vectorize,

预处理大概流程：分词-》建立词典-》留下高频词-》转化成bagofwords->最后分训练测试集，流程主要在preprocess类init里面

keras train：最基本的模型和训练

调试方法：先跑vectorize_data.py,再跑keras_train.py
