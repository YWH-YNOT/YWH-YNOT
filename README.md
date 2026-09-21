# Hi, I'm YWH 👋

[简体中文](README.md) | [English](README.en.md)

> 嵌入式 AI / 机器人系统方向开发者：让感知、推理与控制真正运行在设备上。

我主要围绕 **嵌入式系统、Edge AI、机器人控制与复杂系统集成** 做项目。相比只完成单个算法或外设 Demo，我更关注从传感器采集、协议与实时控制，到端侧推理、执行器和上位机的完整闭环。

## 技术方向

```text
传感器 / 摄像头
       ↓
STM32 / Renesas RA / Jetson
       ↓
Edge AI · 状态估计 · 协议与状态机
       ↓
底盘 / 机械臂 / 无人机 / Web 与桌面端
```

- **嵌入式与实时系统**：C/C++、STM32F1/F4、Renesas RA6M5/RA8P1、ESP32-S3、UART/SPI/I²C/CAN/DMA
- **Edge AI**：PyTorch、YOLO、TinyML、ONNX、TensorRT、Ethos-U NPU、模型量化与端侧部署
- **机器人与控制**：PID、编码器、IMU、麦轮底盘、机械臂、视觉闭环、任务状态机
- **应用与工程化**：Python、FastAPI、Vue 3、PySide6、PostgreSQL、Docker、Linux/Jetson

## 精选项目

| 项目 | 我解决的问题 | 技术关键词 |
| --- | --- | --- |
| [**瑞萨杯 RA8P1 远程精准作业机器人**](https://github.com/YWH-YNOT/renesas-ra8p1-robot-showcase) | 将手套遥操作、双核实时控制、NPU 视觉、麦轮底盘、机械臂与无线图传组成可恢复的分布式闭环 | Cortex-M85/M33、Ethos-U55、IPC、CAN、PySide6 |
| [AI 智能教学平台](https://github.com/YWH-YNOT/ai-teaching-platform-showcase) | 打通教师/学生/管理端、课程 RAG、教学过程管理与多端交付 | Vue 3、FastAPI、Capacitor、SQLite、RAG |
| [智能穿戴手套与 Edge AI](https://github.com/YWH-YNOT/smart-glove-edge-ai) | 打通多路 IMU、STM32 特征帧、RA6M5 SVM 推理与稳定机器人语义 | STM32F407、RA6M5、SVM、CRC16、DMA |
| [嵌入式软件工程 Agent](https://github.com/YWH-YNOT/embedded-software-engineer-agent) | 用资料审查、模块化开发和验证契约约束 AI 辅助固件开发 | Agent workflow、模板、验证、STM32 |
| [工训物流搬运机器人](https://github.com/YWH-YNOT/stm32-logistics-robot) | 工训物流搬运任务中的多串口 DMA、闭环步进驱动与舵机状态机 | STM32F407、UART DMA、步进电机、舵机 |
| [EMB-UAV](https://github.com/YWH-YNOT/EMB-UAV-showcase) | ROS 2、FAST-LIO、MAVROS 与 PX4 的定位桥接、坐标对齐和任务安全 | Python、ROS 2、PX4、MAVROS、FAST-LIO |

> 部分比赛项目因队伍协作、硬件资料或知识产权原因暂不公开完整源码；主页只陈述当前材料能够验证的实现，不把规划项包装成已完成结果。

## 项目成长路线

```text
简易示波器（ADC / OLED / 手工板）
  → 两轮平衡车（IMU / 编码器 / PD + PI）
  → 物流搬运机器人（多串口 DMA / 多执行器）
  → 智能车与空地协同（路径、视觉、无线通信、HMI）
  → AI 教学平台（Web / 移动端 / 课程 RAG）
  → 智能手套（传感器 ML / MCU 推理）
  → RA8P1 机器人（双核 + NPU + 分布式闭环）
```

## 其他工程实践

| 项目 | 已有材料能够验证的内容 | 当前边界 |
| --- | --- | --- |
| 简易示波器 | MCU ADC 采样、OLED 波形显示、按键与手工电路板 | 暂缺源码、原理图和采样指标 |
| STM32 两轮平衡车 | STM32F103、MPU6050 DMP、编码器、PWM、直立 PD 与速度 PI | 归档参数下速度环未启用，仍需重新整车验收 |
| NXP 极速光电车 | 光电循迹车实物与赛道调试经历 | 暂缺芯片型号、控制代码与比赛指标 |
| 无人机动物园巡检 | 动物/目标坐标、巡检路径、禁飞区、网格映射与 HMI 链路 | 与空地协同工程存在代码复用，不重复计算为独立实现 |

这些早期项目保留在技术成长路线中，但不会在证据不足时拆成多个看似完整的公开仓库。

## 我重视的工程原则

- 明确区分“代码构建通过”“板端运行”和“实机验收”；
- 协议包含帧头、版本、序号、校验、超时与故障语义；
- 实时控制与复杂业务分核或分层，避免互相阻塞；
- 用测试、日志、版本和证据入口支撑项目结论。

## 当前关注

正在继续深入 **实时嵌入式系统、模型量化与部署、机器人状态估计与运动控制、ROS 2**。

欢迎通过 GitHub Issues / Discussions 交流嵌入式、Edge AI 与机器人系统工程。
