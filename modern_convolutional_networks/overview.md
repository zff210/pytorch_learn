graph TD
    A["7.1 现代卷积神经网络"] --> B["网络架构"]
    B --> B1["深度网络"]
    B --> B2["模块化设计"]
    B --> B3["残差连接"]
    
    A --> C["关键技术"]
    C --> C1["批量归一化"]
    C --> C2["注意力机制"]
    C --> C3["深度可分离卷积"]
    
    A --> D["优化方法"]
    D --> D1["权重初始化"]
    D --> D2["学习率调度"]
    D --> D3["正则化技术"]
    
    A --> E["框架实现"]
    E --> E1["PyTorch实现"]
    E1 --> E1a["模型定义"]
    E1 --> E1b["训练流程"]
    E --> E2["TensorFlow实现"]
    E2 --> E2a["模型定义"]
    E2 --> E2b["训练流程"]
    
    A --> F["应用场景"]
    F --> F1["图像分类"]
    F --> F2["目标检测"]
    F --> F3["语义分割"]
    F --> F4["实例分割"]
    
    A --> G["发展趋势"]
    G --> G1["轻量级网络"]
    G --> G2["自动化设计"]
    G --> G3["多模态融合"]
    
    A --> H["性能评估"]
    H --> H1["计算效率"]
    H --> H2["内存占用"]
    H --> H3["推理速度"] 