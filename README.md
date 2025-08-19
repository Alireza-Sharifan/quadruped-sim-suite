# Quadruped ROS 2 Simulation Suite (ROS 2 Jazzy + Gazebo Harmonic)

This project began as a personal challenge after I encountered compatibility issues integrating quadruped robots into the ROS 2 Jazzy ecosystem. I implemented and debugged the ros2_control pipeline manually, particularly focusing on plugin behavior in Gazebo Harmonic. All assets were either built by hand or sourced from open repositories, with special attention to TF integrity and sensor realism. This **independent robotics project (non-university affiliated)** demonstrates a full integration attempt of a quadruped robot into a modern ROS 2 Jazzy + Gazebo Harmonic simulation pipeline, including URDF integration, TF frame validation, ros2-control integration trials,and sensor data analysis (LiDAR and IMU, including EKF-based insights).

---

**Key Features:**
- Mesh & URDF integration (corrected paths, Blender-to-RViz/Gazebo validation)
- TF validation and consistency checks (static/dynamic frames, kinematics)
- Custom TF frame insertion for virtual sensors
- ros2_control integration (blocked by plugin/toolchain incompatibilities; basis for mock workflows)
- Real-time LiDAR scan quality evaluation (noise, jitter, data loss)
- IMU analysis for acceleration limits and drift artifacts
- Custom Python tools for LiDAR, IMU, and EKF visualization & analysis
- All simulation assets are open-source or custom-built


**Note:** This repository is intended for academic, research, and demonstration purposes only. 
While the robot structure is inspired by commercial quadruped platforms (e.g., Unitree Go2), all components in this project are independently developed or sourced from open repositories. No proprietary assets were used.

---

**Prepared by:**
**Alireza Sharifan**  
Independent Robotics Integration Engineer (MSc. Mechanical Eng.)  
Visiting Lecturer at Budapest University of Technology and Economics (BME)  
Department of Mechatronics, Optics, and Mechanical Engineering Informatics (MOGI)

Email: alirezasharifan82@gmail.com (Personal), alireza.sharifan@mogi.bme.hu (Affiliation)

## Licensing
All content in this repository is © 2025 Alireza Sharifan — **All rights reserved**.
This material is provided for viewing on GitHub only. No copying, redistribution, or modification is permitted.

---

**Full PDF Report:** [Selected Technical Contributions](docs/Selected-Technical-Contributions.pdf) 

_Where relevant, visual references corresponding to the technical sections in the PDF report are provided under docs/screenshots._ 

**Screenshot Gallery:** [docs/screenshots/](docs/screenshots/)  

Screenshot filenames follow the same numbering as the report (e.g., 1.1, 2.3, …).  
For easy traceability, you may keep the PDF open in one tab and the screenshots folder in another, so that each reference in the text can be directly viewed next to its relevant screenshot file.



