# ITO Masaki | 伊藤 昌樹

Research & Development Engineer interested in **world models, reinforcement learning, and robotics**.

My background connects graduate research in robot learning, hands-on experience with service robots, software engineering in the maritime industry, and current research into learning-based control and 3D perception.

## Education & Career

| Stage | Institution / Company | Research & Experience |
| --- | --- | --- |
| Graduate studies | **Ritsumeikan University — Graduate School of Information Science and Engineering**<br>立命館大学大学院 情報理工学研究科・人間情報科学コース | Master's studies; world models and robotic object grasping. |
| After graduate school | **Weathernews Inc.**<br>株式会社ウェザーニューズ | Software engineering in the maritime business; operational tools and workflow automation. |
| Current | **Chuo Engineering Co., Ltd.**<br>株式会社中央エンジニアリング | Research and development involving AI, simulation-based control, robotics, and point-cloud processing. |

## Graduate Research — World Models for Robotic Grasping

At Ritsumeikan University, I researched **robotic object grasping using world models and generative models**. My interest was in how a robot can learn useful representations of its environment and use those representations for control with limited data.

- Investigated the connection between learned world representations and physical interaction.
- Worked on learning-based approaches to robotic grasping.
- A paper from this research was accepted at **SII — the IEEE/SICE International Symposium on System Integration**.

My broader exploration of generative models and visual control also includes a public [**NewtonianVAE implementation**](https://github.com/ItoMasaki/NewtonianVAE), with tools for data collection, training, and evaluating latent representations for control.

## RoboCup — Service Robot Development

I participated in **RoboCup**, working on a domestic service robot using the **Toyota Human Support Robot (HSR)**.

This experience connected robot-learning research with the practical challenges of building a robot system that interacts with its surroundings.

| Item | Experience |
| --- | --- |
| Platform | Toyota Human Support Robot (HSR) |
| Application | Domestic service robotics |
| Result | Runner-up finish with the team |

## Weathernews — Maritime Software & Operational Automation

At **Weathernews**, I worked in the maritime business as a software engineer, developing and improving internal systems used in daily operations.

- Developed and improved operational tools for maritime services.
- Worked on workflow automation and reducing repetitive manual tasks.
- Gained experience translating operational requirements into software used in day-to-day work.

Alongside this work, I continued studying and implementing machine-learning methods, particularly world models and reinforcement learning.

## Current Research & Development

At **Chuo Engineering**, my current work and research interests span learning-based control, robot learning, and 3D perception. The following sections summarize ongoing directions at a high level.

### Reinforcement Learning & Simulation-Based Control

I investigate how agents learn control policies in simulation and how to improve training stability and evaluation.

- Continuous control with **PPO** and recurrent policies.
- Transferring from **behavior cloning to reinforcement learning**.
- Simulation environments and experimental pipelines using **Python, C++, ROS2, and JSBSim**.
- Multi-agent learning and coordination.

### World Models & Robot Learning

I am exploring how learned representations can connect perception, goals, and robot actions.

- World models and predictive representation learning.
- Goal representations combining **images and language**.
- Imitation learning for manipulation, including **action chunking and flow matching**.
- The relationship between learned dynamics, planning, and control.

These topics include exploratory studies and methods under investigation.

### 3D Point-Cloud Understanding & Terrain Mapping

I work on extracting useful terrain information from large point clouds, with a focus on forest environments.

- **Open-vocabulary point-cloud segmentation** using OpenScene-style distilled features and CLIP text similarity.
- Distinguishing ground, low vegetation, and other scene elements for terrain extraction.
- Connecting ground extraction to **DEM/TIN construction and contour generation**.
- Evaluating pretrained models and identifying where domain-specific data or adaptation is needed.

## Open-Source Research Projects

| Project | Description |
| --- | --- |
| [**PixyzRL**](https://github.com/ItoMasaki/PixyzRL) | A reinforcement learning framework built on Pixyz, supporting PPO, A2C, SAC, and Gymnasium integration. |
| [**NewtonianVAE**](https://github.com/ItoMasaki/NewtonianVAE) | An implementation exploring visual control through physically structured latent representations. |
| [**ROS2Docker**](https://github.com/ItoMasaki/ROS2Docker) | A containerized ROS2 development environment for reproducible robotics research and collaboration. |

## Technical Background

| Area | Tools & Topics |
| --- | --- |
| Programming | Python, C++, Shell |
| Machine Learning | PyTorch, Pixyz, reinforcement learning, world models, imitation learning |
| Robotics & Simulation | ROS2, Gymnasium, JSBSim |
| 3D Perception | Point-cloud segmentation, OpenScene, CLIP, terrain processing |
| Development | Docker, Azure, training pipelines, experiment evaluation |

## Contact

Explore my public work or get in touch through [**GitHub**](https://github.com/ItoMasaki).
