# Hi, I'm YWH 👋

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
| [AI 智能教学平台](https://github.com/YWH-YNOT/work4) | 打通教师/学生/管理端、课堂姿态检测、人脸识别和教学业务 API | Vue 3、FastAPI、Jetson、YOLO Pose |
| [智能穿戴手套](https://github.com/YWH-YNOT/shoutao) | 多路 IMU 采集与 MCU 实时处理，将手势转换为稳定的机器人语义命令 | STM32F407、MPU6050、DMA、TinyML |
| [RA6M5 手势识别链路](https://github.com/YWH-YNOT/project6) | 将手套特征帧、CRC、SVM 推理和分周期命令调度拆成可验证的分层系统 | RA6M5、FSP、SVM、CRC16、AGT |
| [嵌入式软件工程 Agent](https://github.com/YWH-YNOT/embedded-software-engineer-agent) | 用资料审查、模块化开发和验证契约约束 AI 辅助固件开发 | Agent workflow、模板、验证、STM32 |
| [物流搬运机器人](https://github.com/YWH-YNOT/-) | 建立多串口 DMA、闭环步进驱动与舵机状态机的执行器控制基线 | STM32F407、UART DMA、步进电机、舵机 |

> 部分比赛项目因队伍协作、硬件资料或知识产权原因暂不公开完整源码；主页只陈述当前材料能够验证的实现，不把规划项包装成已完成结果。

## 项目成长路线

```text
简易示波器（ADC / OLED / 手工板）
  → 两轮平衡车（IMU / 编码器 / PD + PI）
  → 物流搬运机器人（多串口 DMA / 多执行器）
  → 智能车与空地协同（路径、视觉、无线通信、HMI）
  → AI 教学平台（Web / Jetson / 视觉 AI）
  → 智能手套（传感器 ML / MCU 推理）
  → RA8P1 机器人（双核 + NPU + 分布式闭环）
```

## 我重视的工程原则

- 明确区分“代码构建通过”“板端运行”和“实机验收”；
- 协议包含帧头、版本、序号、校验、超时与故障语义；
- 实时控制与复杂业务分核或分层，避免互相阻塞；
- 用测试、日志、版本和证据入口支撑项目结论。

## 当前关注

正在继续深入 **实时嵌入式系统、模型量化与部署、机器人状态估计与运动控制、ROS 2**。

欢迎通过 GitHub Issues / Discussions 交流嵌入式、Edge AI 与机器人系统工程。
