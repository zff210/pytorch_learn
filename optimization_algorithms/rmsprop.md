graph TD
    A["11.8 RMSProp算法"] --> B["基本概念"]
    B --> B1["梯度平方移动平均"]
    B --> B2["学习率调整"]
    B --> B3["参数更新"]
    
    A --> C["算法流程"]
    C --> C1["初始化移动平均变量"]
    C --> C2["计算梯度"]
    C --> C3["更新移动平均"]
    C --> C4["更新参数"]
    
    A --> D["实现方法"]
    D --> D1["PyTorch实现"]
    D1 --> D1a["torch.optim.RMSprop"]
    D1 --> D1b["自定义实现"]
    D --> D2["TensorFlow实现"]
    D2 --> D2a["tf.keras.optimizers.RMSprop"]
    D2 --> D2b["自定义实现"]
    
    A --> E["优化技巧"]
    E --> E1["衰减率选择"]
    E --> E2["初始学习率选择"]
    E --> E3["梯度裁剪"]
    
    A --> F["收敛性分析"]
    F --> F1["收敛条件"]
    F --> F2["收敛速度"]
    F --> F3["移动平均效应分析"]
    
    A --> G["变体算法"]
    G --> G1["带动量的RMSProp"]
    G --> G2["Adadelta"]
    G --> G3["Adam"]
    
    A --> H["应用场景"]
    H --> H1["非平稳目标"]
    H --> H2["深度学习"]
    H --> H3["强化学习"]
    
    A --> I["常见问题"]
    I --> I1["衰减率选择"]
    I --> I2["学习率选择"]
    I --> I3["数值稳定性"]
    I --> I4["内存消耗"]
    
    A --> J["优势特点"]
    J --> J1["自适应学习率"]
    J --> J2["处理非平稳目标"]
    J --> J3["减少手动调参"] 