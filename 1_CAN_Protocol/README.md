## Phase 0.5 结构复刻

**目标:** 解构 ROS 逻辑，映射为博士论文的架构。  

**任务:**  
1. [ ] 运行 qt_graph 并保存截图 os_rqt_graph.png。  
2. [ ] 编写 os_data_flow.md 梳理数据流。  
3. [ ] 创建 rchitecture_mapping.md 表格，将 ROS 节点与论文图 6.3 模块对应。  

**交付物:** rchitecture_mapping.md
"@ | Out-File -Encoding utf8 "0_System_Architecture\README.md"

# === Phase 1 ===
@"
## Phase 1 CAN 通信科研化

**目标:** 建立 Orin 与 STM32 的 CAN 通信。  

**任务:**  
1. 采购 STM32 + TJA1050 + USB-CAN。  
2. 创建 USV_CAN_Protocol_v1.0.md 定义 PGN。  
3. 在 STM32 上编写 CAN 解析程序。  
4. 在 Orin 上编写 orin_can_bridge.py 发送 PGN 0x10 帧。  

**交付物:** 协议文档与可通信代码。
