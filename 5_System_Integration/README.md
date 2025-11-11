## Phase 3 控制算法验证

**目标:** 在 ROS 平台上实现 Pure Pursuit 算法。  

**任务:**  
1. 研读 Pure Pursuit 论文。  
2. 实现 my_pure_pursuit_node.py。  
3. 记录 error.csv 并绘制误差曲线。  

**交付物:** 源码 + 	racking_performance_report.md
"@ | Out-File -Encoding utf8 "3_Control_Algorithms\README.md"

# === Phase 4 ===
@"
## Phase 4 动力分配与建模

**目标:** 实现 3-DOF 模型与动力分配模块。  

**任务:**  
1. 推导 3-DOF 模型。  
2. 系统辨识实验。  
3. 实现 control_allocation.py。  

**交付物:** 函数库 + system_identification_report.md
"@ | Out-File -Encoding utf8 "4_Dynamic_Modeling\README.md"

# === Phase 5 ===
@"
## Phase 5 平台复现

**目标:** 在 ROS 船上实现完整控制链路。  

**任务:**  
1. 串联 Pure Pursuit、控制分配、CAN 通信与 STM32 控制。  
2. 测量端到端延迟并绘制延迟链路图。  

**交付物:** 系统复现报告 + 延迟分析图。
