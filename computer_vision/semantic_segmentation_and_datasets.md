graph TD
    A["13.9 语义分割和数据集"] --> B["图像分割和实例分割"]
    B --> B1["语义分割"]
    B1 --> B1a["像素级分类"]
    B1 --> B1b["类别预测"]
    B1 --> B1c["边界处理"]
    
    B --> B2["实例分割"]
    B2 --> B2a["实例区分"]
    B2 --> B2b["掩码生成"]
    B2 --> B2c["边界优化"]
    
    B --> B3["全景分割"]
    B3 --> B3a["语义分割"]
    B3 --> B3b["实例分割"]
    B3 --> B3c["融合策略"]
    
    A --> C["Pascal VOC2012 语义分割数据集"]
    C --> C1["数据集介绍"]
    C1 --> C1a["数据规模"]
    C1 --> C1b["类别定义"]
    C1 --> C1c["标注格式"]
    
    C --> C2["数据特点"]
    C2 --> C2a["图像质量"]
    C2 --> C2b["场景多样性"]
    C2 --> C2c["标注质量"]
    
    C --> C3["使用方式"]
    C3 --> C3a["数据加载"]
    C3 --> C3b["预处理"]
    C3 --> C3c["评估方法"]
    
    A --> D["实现方法"]
    D --> D1["网络架构"]
    D1 --> D1a["全卷积网络"]
    D1 --> D1b["编码器-解码器"]
    D1 --> D1c["注意力机制"]
    
    D --> D2["训练策略"]
    D2 --> D2a["损失函数"]
    D2 --> D2b["数据增强"]
    D2 --> D2c["优化器"]
    
    D --> D3["评估指标"]
    D3 --> D3a["像素准确率"]
    D3 --> D3b["平均交并比"]
    D3 --> D3c["类别准确率"]
    
    A --> E["应用场景"]
    E --> E1["场景理解"]
    E --> E2["自动驾驶"]
    E --> E3["医学图像"]
    E --> E4["遥感图像"]
    
    A --> F["注意事项"]
    F --> F1["计算效率"]
    F --> F2["内存占用"]
    F --> F3["分割精度"]
    F --> F4["模型复杂度"] 