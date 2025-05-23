graph TD
    A["14.8 来自Transformers的双向编码器表示（BERT）"] --> B["从上下文无关到上下文敏感"]
    B --> B1["传统词嵌入"]
    B1 --> B1a["Word2Vec"]
    B1 --> B1b["GloVe"]
    B1 --> B1c["FastText"]
    B1 --> B1d["ELMo"]
    
    B --> B2["上下文表示"]
    B2 --> B2a["双向编码"]
    B2 --> B2b["位置编码"]
    B2 --> B2c["注意力机制"]
    B2 --> B2d["多层表示"]
    
    B --> B3["预训练任务"]
    B3 --> B3a["掩码语言模型"]
    B3 --> B3b["下一句预测"]
    B3 --> B3c["多任务学习"]
    B3 --> B3d["领域适应"]
    
    A --> C["从特定任务到任务无关"]
    C --> C1["传统方法"]
    C1 --> C1a["任务特定模型"]
    C1 --> C1b["特征工程"]
    C1 --> C1c["领域适应"]
    C1 --> C1d["迁移学习"]
    
    C --> C2["预训练模型"]
    C2 --> C2a["通用表示"]
    C2 --> C2b["微调策略"]
    C2 --> C2c["多任务学习"]
    C2 --> C2d["零样本学习"]
    
    C --> C3["应用场景"]
    C3 --> C3a["文本分类"]
    C3 --> C3b["问答系统"]
    C3 --> C3c["命名实体识别"]
    C3 --> C3d["机器翻译"]
    
    A --> D["BERT：结合两个最佳方案"]
    D --> D1["模型架构"]
    D1 --> D1a["Transformer编码器"]
    D1 --> D1b["多头注意力"]
    D1 --> D1c["前馈网络"]
    D1 --> D1d["层归一化"]
    
    D --> D2["预训练策略"]
    D2 --> D2a["掩码语言模型"]
    D2 --> D2b["下一句预测"]
    D2 --> D2c["训练目标"]
    D2 --> D2d["优化方法"]
    
    D --> D3["微调方法"]
    D3 --> D3a["任务特定头"]
    D3 --> D3b["学习率调度"]
    D3 --> D3c["正则化策略"]
    D3 --> D3d["早停机制"]
    
    A --> E["输入表示"]
    E --> E1["词嵌入"]
    E1 --> E1a["词向量"]
    E1 --> E1b["位置编码"]
    E1 --> E1c["段嵌入"]
    E1 --> E1d["特殊标记"]
    
    E --> E2["预处理"]
    E2 --> E2a["分词"]
    E2 --> E2b["填充"]
    E2 --> E2c["截断"]
    E2 --> E2d["掩码"]
    
    E --> E3["特征提取"]
    E3 --> E3a["上下文表示"]
    E3 --> E3b["注意力权重"]
    E3 --> E3c["层间特征"]
    E3 --> E3d["池化策略"]
    
    A --> F["预训练任务"]
    F --> F1["掩码语言模型"]
    F1 --> F1a["掩码策略"]
    F1 --> F1b["预测目标"]
    F1 --> F1c["损失函数"]
    F1 --> F1d["优化方法"]
    
    F --> F2["下一句预测"]
    F2 --> F2a["句子对构建"]
    F2 --> F2b["分类目标"]
    F2 --> F2c["损失函数"]
    F2 --> F2d["优化方法"]
    
    F --> F3["多任务学习"]
    F3 --> F3a["任务权重"]
    F3 --> F3b["联合训练"]
    F3 --> F3c["交替训练"]
    F3 --> F3d["渐进训练"]
    
    A --> G["注意事项"]
    G --> G1["计算资源"]
    G1 --> G1a["GPU需求"]
    G1 --> G1b["内存使用"]
    G1 --> G1c["训练时间"]
    G1 --> G1d["推理速度"]
    
    G --> G2["数据质量"]
    G2 --> G2a["语料规模"]
    G2 --> G2b["领域覆盖"]
    G2 --> G2c["数据清洗"]
    G2 --> G2d["噪声处理"]
    
    G --> G3["应用限制"]
    G3 --> G3a["领域适应"]
    G3 --> G3b["多语言支持"]
    G3 --> G3c["实时性要求"]
    G3 --> G3d["资源限制"] 