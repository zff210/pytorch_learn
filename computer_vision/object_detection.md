graph TD
    A["13.2 目标检测"] --> B["两阶段检测器"]
    B --> B1["R-CNN系列"]
    B --> B2["特征提取"]
    B --> B3["区域提议"]
    B --> B4["分类与回归"]
    
    A --> C["单阶段检测器"]
    C --> C1["YOLO系列"]
    C --> C2["SSD"]
    C --> C3["RetinaNet"]
    C --> C4["FCOS"]
    
    A --> D["无锚框检测器"]
    D --> D1["CenterNet"]
    D --> D2["CornerNet"]
    D --> D3["RepPoints"]
    D --> D4["DETR"]
    
    A --> E["实现方法"]
    E --> E1["PyTorch实现"]
    E1 --> E1a["mmdetection"]
    E1 --> E1b["detectron2"]
    E --> E2["TensorFlow实现"]
    E2 --> E2a["TensorFlow Object Detection API"]
    E2 --> E2b["TFOD API"]
    
    A --> F["优化技巧"]
    F --> F1["数据增强"]
    F --> F2["损失函数设计"]
    F --> F3["后处理优化"]
    F --> F4["模型压缩"]
    
    A --> G["应用场景"]
    G --> G1["通用目标检测"]
    G --> G2["人脸检测"]
    G --> G3["行人检测"]
    G --> G4["交通标志检测"]
    
    A --> H["常见问题"]
    H --> H1["小目标检测"]
    H --> H2["密集目标检测"]
    H --> H3["实时性要求"]
    H --> H4["计算资源限制"]
    
    A --> I["优势特点"]
    I --> I1["定位准确"]
    I --> I2["分类精确"]
    I --> I3["实时性好"]
    I --> I4["应用广泛"] 