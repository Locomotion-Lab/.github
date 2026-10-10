<div align="center">
  <img src="https://raw.githubusercontent.com/Locomotion-Lab/.github/main/profile/assets/logo.svg" alt="Locomotion-Lab Logo" width="130" />

  # Locomotion-Lab

  **Robotics · Perception · Navigation · Control**

  机器人软件、感知导航、运动控制与嵌入式系统
</div>

---

## 关于我们 | About

**Locomotion-Lab** 是课题组开展机器人软件与系统开发的 GitHub 协作组织，用于沉淀机器人平台相关的驱动、仿真工程、嵌入式固件及开发工具。

我们关注从硬件设备接入到机器人自主运动的完整工程链路，并通过可维护、可复用的代码支持持续的研究与实验。

## 技术方向 | What We Work On

| 方向 | 相关技术与工程实践 |
| --- | --- |
| 🤖 多机器人平台 | 四足机器人、轮式移动机器人、无人机的软件集成与控制 |
| 📡 感知与定位 | 相机、激光雷达、IMU、GNSS 等传感器接入；激光惯导里程计与建图 |
| 🧭 仿真与自主导航 | ROS / ROS 2、Gazebo、PX4、Nav2、SLAM 与路径规划 |
| ⚙️ 嵌入式系统 | STM32、ESP32、传感器通信、状态估计与控制程序 |

## 项目与代码 | Repositories

组织仓库涵盖设备驱动、ROS 工作空间、仿真环境、嵌入式固件和控制工具。以下项目使用当前仓库名称，Topics 与 GitHub 设置保持一致（2026-10-10 更新）。

| 方向 | 仓库 | 简介 | Topics |
| --- | --- | --- | --- |
| 驱动与感知 | [ros-driver](https://github.com/Locomotion-Lab/ros-driver) | 多传感器接入、SLAM 与标定，涵盖 ROS 1 / ROS 2 工作空间。 | `driver` · `ros` · `ros2` |
| Go2 实机 | [go2-ros-driver](https://github.com/Locomotion-Lab/go2-ros-driver) | Unitree Go2 ROS 2 驱动与传感器工作空间。 | `driver` · `go2` · `ros2` |
| 无人机软件 | [uav-ros-driver](https://github.com/Locomotion-Lab/uav-ros-driver) | 无人机 ROS 1 工作空间、MAVROS 与运动控制。 | `driver` · `ros` · `uav` |
| Go2 仿真 | [go2-sim](https://github.com/Locomotion-Lab/go2-sim) | Go2 Gazebo 仿真、建图与 Nav2 导航。 | `go2` · `ros2` · `simulation` |
| PX4 仿真 | [px4-sim](https://github.com/Locomotion-Lab/px4-sim) | PX4 / MAVROS / Gazebo 的 Docker 仿真开发环境。 | `px4` · `simulation` |
| STM32 固件 | [stm32-firmware](https://github.com/Locomotion-Lab/stm32-firmware) | STM32H743 飞控、状态估计与控制工程。 | `firmware` · `stm32` |
| ESP32 固件 | [esp32-firmware](https://github.com/Locomotion-Lab/esp32-firmware) | ESP32-S3 Web 与串口数据采集控制。 | `esp32` · `firmware` |
| 底盘遥控 | [scout-keyboard-control](https://github.com/Locomotion-Lab/scout-keyboard-control) | Scout 底盘 ROS 2 键盘遥控包。 | `controller` · `development` |

**按标签浏览**：[驱动 · driver](https://github.com/orgs/Locomotion-Lab/repositories?q=topic%3Adriver) · [仿真 · simulation](https://github.com/orgs/Locomotion-Lab/repositories?q=topic%3Asimulation) · [固件 · firmware](https://github.com/orgs/Locomotion-Lab/repositories?q=topic%3Afirmware) · [ROS 2 · ros2](https://github.com/orgs/Locomotion-Lab/repositories?q=topic%3Aros2) · [控制 · controller](https://github.com/orgs/Locomotion-Lab/repositories?q=topic%3Acontroller)

[car-driver](https://github.com/Locomotion-Lab/car-driver) 与 [software](https://github.com/Locomotion-Lab/software) 当前标记为 `empty`，属于待建设的占位仓库；可通过 [empty 标签](https://github.com/orgs/Locomotion-Lab/repositories?q=topic%3Aempty) 查看。

- [浏览全部公开仓库](https://github.com/orgs/Locomotion-Lab/repositories?type=public)
- **团队成员**：登录并加入组织后，可在组织主页切换至 **Member** 视图，查看项目导航、分支说明及入门指引。

> 项目的可见性、可用性和维护状态以各仓库的实际设置与 README 为准。

## 交流与协作 | Collaboration

我们通过 GitHub 管理代码版本、项目文档与技术交流。访问内部资源或参与团队项目，请联系课题组/组织管理员。

<div align="center">
  <sub>Locomotion-Lab · Built through collaboration.</sub>
</div>
