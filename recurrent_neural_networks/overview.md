graph TD
    A["8.1 循环神经网络"] --> B["基本概念"]
    B --> B1["时序数据"]
    B --> B2["隐藏状态"]
    B --> B3["循环连接"]
    
    A --> C["网络结构"]
    C --> C1["输入层"]
    C --> C2["隐藏层"]
    C --> C3["输出层"]
    
    A --> D["计算过程"]
    D --> D1["前向传播"]
    D --> D2["反向传播"]
    D --> D3["梯度计算"]
    
    A --> E["框架实现"]
    E --> E1["PyTorch实现"]
    E1 --> E1a["nn.RNN"]
    E1 --> E1b["nn.LSTM"]
    E --> E2["TensorFlow实现"]
    E2 --> E2a["tf.keras.layers.RNN"]
    E2 --> E2b["tf.keras.layers.LSTM"]
    
    A --> F["应用场景"]
    F --> F1["自然语言处理"]
    F --> F2["时间序列预测"]
    F --> F3["语音识别"]
    
    A --> G["优化方法"]
    G --> G1["梯度裁剪"]
    G --> G2["权重初始化"]
    G --> G3["正则化"]
    
    A --> H["挑战与解决方案"]
    H --> H1["梯度消失"]
    H --> H2["梯度爆炸"]
    H --> H3["长期依赖"] 