graph TD
    A["13.3 语义分割"] --> B["全卷积网络"]
    B --> B1["FCN"]
    B --> B2["空洞卷积"]
    B --> B3["特征融合"]
    B --> B4["上采样方法"]
    
    A --> C["编码器-解码器"]
    C --> C1["U-Net"]
    C --> C2["SegNet"]
    C --> C3["DeepLab系列"]
    C --> C4["PSPNet"]
    
    A --> D["注意力机制"]
    D --> D1["空间注意力"]
    D --> D2["通道注意力"]
    D --> D3["自注意力"]
    D --> D4["交叉注意力"]
    
    A --> E["实现方法"]
    E --> E1["PyTorch实现"]
    E1 --> E1a["torchvision.models.segmentation"]
    E1 --> E1b["mmsegmentation"]
    E --> E2["TensorFlow实现"]
    E2 --> E2a["tf.keras.applications"]
    E2 --> E2b["TF-Slim"]
    
    A --> F["优化技巧"]
    F --> F1["损失函数设计"]
    F --> F2["数据增强"]
    F --> F3["模型压缩"]
    F --> F4["后处理优化"]
    
    A --> G["应用场景"]
    G --> G1["场景理解"]
    G --> G2["医学图像分割"]
    G --> G3["自动驾驶"]
    G --> G4["遥感图像分割"]
    
    A --> H["常见问题"]
    H --> H1["边界模糊"]
    H --> H2["类别不平衡"]
    H --> H3["计算资源"]
    H --> H4["实时性要求"]
    
    A --> I["优势特点"]
    I --> I1["像素级分类"]
    I --> I2["场景理解"]
    I --> I3["端到端学习"]
    I --> I4["应用广泛"] 