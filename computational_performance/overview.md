graph TD
    A["第12章 计算性能"] --> B["12.1 编译器和解释器"]
    A --> C["12.2 异步计算"]
    A --> D["12.3 自动并行"]
    A --> E["12.4 硬件加速器"]
    A --> F["12.5 多GPU训练"]
    A --> G["12.6 参数服务器"]
    
    B --> B1["编译过程"]
    B --> B2["解释执行"]
    B --> B3["JIT编译"]
    
    C --> C1["异步编程"]
    C --> C2["事件循环"]
    C --> C3["回调函数"]
    
    D --> D1["数据并行"]
    D --> D2["模型并行"]
    D --> D3["流水线并行"]
    
    E --> E1["GPU加速"]
    E --> E2["TPU加速"]
    E --> E3["FPGA加速"]
    
    F --> F1["数据并行训练"]
    F --> F2["模型并行训练"]
    F --> F3["混合并行训练"]
    
    G --> G1["参数同步"]
    G --> G2["梯度聚合"]
    G --> G3["负载均衡"] 