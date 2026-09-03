# Donghee

### Robotics & Machine Vision Developer

I build **machine vision and robotic systems** that connect computer vision,
AI, and real-world hardware.

Currently working as a **Machine Vision Developer** and conducting undergraduate
research in robotics at **AIRO Lab, Hanyang University ERICA**.

My interests include **robot perception, autonomous systems, vision inspection,
and robot manipulation**.

---

## Experience

### 🔬 Undergraduate Researcher — AIRO Lab
**Hanyang University ERICA** · Feb. 2026 – Present

- Developing and experimenting with **ROS 2-based robotic systems**
- Working with **robot manipulation, motion planning, and perception**
- Integrating cameras, sensors, and robotic hardware
- Developing and testing software on physical robot platforms

### 💼 Machine Vision Developer

- Developing industrial **machine vision and vision inspection systems**
- Camera integration and image acquisition
- Image processing and computer vision
- AI-based object detection
- Industrial automation software
- Hardware–software integration

---

## Education

### 🎓 Hanyang University ERICA

**School of Smart Convergence Engineering**  
**Major in Robotics & Convergence**

Mar. 2022 – Feb. 2027 (Expected)

---

## 🛠️ Tech Stack

### Robotics

![ROS2](https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

`ROS 2` `MoveIt 2` `Nav2` `SLAM` `Robot Manipulation`

### Computer Vision & AI

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NVIDIA](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)

`OpenCV` `YOLO` `PyTorch` `TensorRT` `OCR` `Image Processing`

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)

### Software & Frameworks

![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

`Avalonia` `MVVM` `FastAPI` `MQTT` `TCP/IP`

### Hardware & Platforms

![NVIDIA](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

`Universal Robots` `LiDAR` `Industrial Cameras`

---

# Projects

## 🧯 TETRA — Autonomous Fire Extinguisher Inspection Robot

**Graduation Project · Hanyang University ERICA**

An autonomous mobile robot designed to perform **fire extinguisher inspection
in large indoor environments**.

TETRA combines autonomous navigation with computer vision and deep learning
to locate and inspect fire extinguishers, including pressure gauge analysis
and manufacturing-date recognition.

### 🎥 Demo

<a href="https://www.youtube.com/watch?v=Pz11rFRjoiU">
  <img src="https://i.ytimg.com/vi/Pz11rFRjoiU/hqdefault.jpg"
       alt="TETRA Autonomous Fire Extinguisher Inspection Robot Demo"
       width="600">
</a>

▶ **Click the image to watch the demonstration**

### Key Features

- Autonomous navigation using **ROS 2 & Nav2**
- LiDAR-based localization and obstacle avoidance
- Fire extinguisher detection using **YOLO**
- Manufacturing-date recognition using **OCR**
- Pressure gauge analysis using **OpenCV**
- Multi-camera inspection system
- Autonomous waypoint navigation
- Embedded deployment on **NVIDIA Jetson**

### System Overview

```text
                 ┌──────────────┐
                 │    LiDAR     │
                 └──────┬───────┘
                        │
                        ▼
               ┌────────────────┐
               │ ROS 2 / Nav2   │
               │ Localization   │
               │ Path Planning  │
               └───────┬────────┘
                       │
                       ▼
              Autonomous Navigation
                       │
                       ▼
              Fire Extinguisher
                   Inspection
                       │
            ┌──────────┴──────────┐
            ▼                     ▼
      Object Detection      Image Acquisition
           YOLO                  Cameras
            │                     │
            └──────────┬──────────┘
                       ▼
               ┌───────────────┐
               │ Vision System │
               └───────┬───────┘
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
      Pressure Gauge       Manufacturing Date
        Inspection               OCR
        (OpenCV)
             │                   │
             └─────────┬─────────┘
                       ▼
                Inspection Result
