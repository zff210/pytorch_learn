graph TD
    A["4.3 多层感知机的简洁实现"] --> B["使用深度学习框架"]
    B --> B1["PyTorch实现"]
    B1 --> B1a["nn.Sequential"]
    B1 --> B1b["nn.Linear"]
    B1 --> B1c["nn.ReLU"]
    B1 --> B1d["nn.CrossEntropyLoss"]
    B --> B2["TensorFlow实现"]
    B2 --> B2a["tf.keras.Sequential"]
    B2 --> B2b["tf.keras.layers.Dense"]
    B2 --> B2c["tf.keras.layers.Activation"]
    B2 --> B2d["tf.keras.losses.SparseCategoricalCrossentropy"]
    
    A --> C["模型定义"]
    C --> C1["网络结构"]
    C --> C2["激活函数"]
    C --> C3["损失函数"]
    C --> C4["优化器"]
    
    A --> D["训练过程"]
    D --> D1["数据加载"]
    D --> D2["前向传播"]
    D --> D3["计算损失"]
    D --> D4["反向传播"]
    D --> D5["参数更新"]
    
    A --> E["模型评估"]
    E --> E1["准确率"]
    E --> E2["损失曲线"]
    E --> E3["混淆矩阵"]
    
    A --> F["超参数调优"]
    F --> F1["学习率"]
    F --> F2["批量大小"]
    F --> F3["隐藏层大小"]
    F --> F4["激活函数选择"] 