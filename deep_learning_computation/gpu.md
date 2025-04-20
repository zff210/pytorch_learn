graph TD
    A["5.6 GPU"] --> B["基本概念"]
    B --> B1["GPU加速"]
    B --> B2["CUDA"]
    B --> B3["GPU内存"]
    
    A --> C["设备管理"]
    C --> C1["设备选择"]
    C --> C2["设备切换"]
    C --> C3["多GPU支持"]
    
    A --> D["数据迁移"]
    D --> D1["CPU到GPU"]
    D --> D2["GPU到CPU"]
    D --> D3["GPU间传输"]
    
    A --> E["框架实现"]
    E --> E1["PyTorch实现"]
    E1 --> E1a["to(device)"]
    E1 --> E1b["cuda()"]
    E --> E2["TensorFlow实现"]
    E2 --> E2a["with tf.device"]
    E2 --> E2b["tf.config.set_visible_devices"]
    
    A --> F["性能优化"]
    F --> F1["批处理大小"]
    F --> F2["内存管理"]
    F --> F3["并行计算"]
    
    A --> G["常见问题"]
    G --> G1["内存溢出"]
    G --> G2["设备不兼容"]
    G --> G3["性能瓶颈"] 