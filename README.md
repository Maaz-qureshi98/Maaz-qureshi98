<div align="center">

<img src="assets/vla-banner.svg" width="100%" alt="Maaz Qureshi: Vision → Language → Action"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=720&lines=Teaching+robots+to+see%2C+reason%2C+and+act.;Vision-Language-Action+policies+on+real+robots;Multi-robot+mapping+%C2%B7+4D+mmWave+radar+%C2%B7+5G;Franka+%C2%B7+OpenArm+%C2%B7+ESP32+swarms+%C2%B7+ROS+2" alt="Typing SVG"/></a>

[![Portfolio](https://img.shields.io/badge/Portfolio-0b1020?style=for-the-badge&logo=googlechrome&logoColor=38bdf8)](https://maaz-qureshi98.github.io/Portfolio-Maaz/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maaz-ahmad-046c/)
[![Google Scholar](https://img.shields.io/badge/Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.ca/citations?user=hC7tswoAAAAJ&hl=en)
[![Email](https://img.shields.io/badge/Email-a78bfa?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:m23qures@uwaterloo.ca)

</div>

---

### 🤖 About me

I'm a **Research Engineer in Embodied AI and robot learning**. I teach robots to **perceive, reason, and act** in the physical world.

- 🧠 **Policy learning:** Vision-Language-Action (VLA) models, diffusion policies, imitation learning and RL, deployed on real manipulators
- 👁️ **Perception:** RGB-D and 4D mmWave radar fusion, SLAM, VLMs, real-time CUDA/TensorRT pipelines
- 🦾 **Systems:** multi-robot autonomy, 5G-connected AMRs, cobots (Franka Panda, OpenArm), ESP32 robot swarms
- 🎓 **MASc, Mechatronics Engineering, University of Waterloo**: worked with Apple, UW RoboHub, Keysight and Rogers on smart-factory robotics

### 🔁 How my work fits together

```mermaid
flowchart LR
    subgraph V["👁️ Vision"]
        A1[RGB-D cameras] --> P[Perception<br/>SLAM · detection · segmentation]
        A2[4D mmWave radar] --> P
    end
    subgraph L["🧠 Language & Reasoning"]
        P --> VLM[VLM / VLA policy]
        I["“pick up the red cup”"] --> VLM
    end
    subgraph A["🦾 Action"]
        VLM --> C[Closed-loop control]
        C --> R1[Franka Panda]
        C --> R2[OpenArm bimanual]
        C --> R3[Multi-robot fleets]
    end
```

### 🚀 Featured research

| Project | What it does | Venue |
|---|---|---|
| 🛰️ [**CRADMap**](https://github.com/Maaz-qureshi98/CRADMap-Multi-Robot-Mapping) | Distributed volumetric mapping with 5G-connected multi-robots and 4D mmWave radar perception | **IEEE ICARM 2025** |
| 📡 [**RAPTAR**](https://github.com/Maaz-qureshi98/RAPTAR-Motion-Planning) | Autonomous hemispherical mmWave radar pattern measurement with a Franka Panda cobot (ROS, MoveIt) | **IEEE AP-S/URSI 2026** |
| 🐝 [**Swarm Autobots**](https://github.com/Maaz-qureshi98/Swarm-Autobots) | Decentralized formation control for ESP32 robot teams over ESP-NOW, from simulation to hardware | Publication in prep |
| 🦾 [**OpenArm CAN**](https://github.com/Maaz-qureshi98/OpenArm-CAN) | One-file bring-up and control for a bimanual OpenArm over CAN-FD | Tooling |
| 🌊 [**4D mmWave Radar ROS 2**](https://github.com/Maaz-qureshi98/Radar-ROS2_Perception-4DmmWave) | ROS 2 perception for Altos 4D mmWave radar | Tooling |
| 📶 [**5G Quectel drivers**](https://github.com/Maaz-qureshi98/5G-quectel-linux_drivers) | 5G modem drivers for Ubuntu 22.04 robots | Tooling |

### 🛠️ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,c,pytorch,ros,docker,linux,opencv,swift,git&perline=10" alt="Skills"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/MoveIt-22314E?style=flat-square&logo=ros&logoColor=white"/>
  <img src="https://img.shields.io/badge/ORB--SLAM3-334155?style=flat-square"/>
  <img src="https://img.shields.io/badge/Hugging%20Face%20LeRobot-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/ARKit-000000?style=flat-square&logo=apple&logoColor=white"/>
</p>

### 📈 Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Maaz-qureshi98/Maaz-qureshi98/output/snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/Maaz-qureshi98/Maaz-qureshi98/output/snake.svg" alt="Contribution snake"/>
  </picture>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Maaz-qureshi98&theme=tokyonight&hide_border=true&background=0b1020" alt="GitHub streak"/>
</p>

<div align="center"><sub>🛠️ Building robots that understand what they see and do what they're told.</sub></div>
