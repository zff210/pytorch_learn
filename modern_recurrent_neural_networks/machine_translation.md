graph TD
    A["8.11 机器翻译与数据集"] --> B["数据集"]
    B --> B1["WMT"]
    B --> B2["IWSLT"]
    B --> B3["Multi30k"]
    
    A --> C["数据预处理"]
    C --> C1["分词"]
    C --> C2["词表构建"]
    C --> C3["序列填充"]
    
    A --> D["模型架构"]
    D --> D1["编码器"]
    D --> D2["解码器"]
    D --> D3["注意力机制"]
    
    A --> E["实现方法"]
    E --> E1["PyTorch实现"]
    E1 --> E1a["nn.Transformer"]
    E1 --> E1b["自定义实现"]
    E --> E2["TensorFlow实现"]
    E2 --> E2a["tf.keras.layers.Transformer"]
    E2 --> E2b["自定义层"]
    
    A --> F["评估指标"]
    F --> F1["BLEU"]
    F --> F2["ROUGE"]
    F --> F3["METEOR"]
    
    A --> G["优化技巧"]
    G --> G1["学习率调度"]
    G --> G2["标签平滑"]
    G --> G3["束搜索"]
    
    A --> H["应用场景"]
    H --> H1["文本翻译"]
    H --> H2["语音翻译"]
    H --> H3["多语言翻译"] 