<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffd1e8,50:f08cb4,100:e75480&height=240&section=header&text=Hi,%20I'm%20Bipasha%20🪼&fontSize=50&fontColor=ffffff&animation=twinkling&fontAlignY=36&desc=Mechanical%20Engineering%20Student%20%C2%B7%20Tezpur%20University&descSize=18&descAlignY=56" width="100%"/>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=E75480&center=true&vCenter=true&width=700&lines=I+design+robots+from+CAD+to+control;SolidWorks+%E2%86%92+ANSYS+%E2%86%92+URDF+%E2%86%92+ROS2;1+kHz+adaptive+control+on+an+8-DOF+exoskeleton;Open+to+robotics+internships+and+grad+roles" alt="Typing intro" />
</p>

<p align="center">
<a href="https://bipasha-deka.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-e75480?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/bipasha-deka/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:bipashadeka2005@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

### About

I'm a final-year **B.Tech Mechanical Engineering student** at **Tezpur University**, Assam.

Most of my work is on the mechanical side of robots. I model the parts in SolidWorks and check them with FEA. After that I work out the kinematics and control, and test it all in ROS2 and Gazebo. I've also done 3D printing and the usual workshop work.

Currently open to internships and graduate roles in robotics and mechanical design, including automation.

### How I build a robot

```mermaid
flowchart LR
  A[SolidWorks CAD] --> B[ANSYS FEA]
  B --> C[URDF model]
  C --> D[Kinematics]
  D --> E[MRAC control]
  E --> F[ROS2 + Gazebo test]
  F -. redesign .-> A
  classDef pink fill:#ffd1e8,stroke:#e75480,stroke-width:2px,color:#4a0d27
  class A,B,C,D,E,F pink
```

### By the numbers

<table align="center">
<tr>
<td align="center"><h2>1 kHz</h2>MRAC control loop</td>
<td align="center"><h2>24</h2>parameters estimated online</td>
<td align="center"><h2>0.13°</h2>best tracking RMSE</td>
<td align="center"><h2>100 mm</h2>quadruped stability margin</td>
<td align="center"><h2>0.12%</h2>FEA vs hand calcs</td>
</tr>
</table>

---

### Projects

| Project | What I did | Tools |
|---|---|---|
| [8-DOF Lower-Limb Exoskeleton](https://github.com/bipashadeka/ROS2-MRAC-Lower-Limb-Exoskeleton) | Built the URDF and a 1 kHz MRAC controller in C++ that estimates 24 dynamic parameters online, with torque and slew-rate limits. Tracking RMSE is 0.13° to 0.74°. | ROS2, C++, URDF, RViz2 |
| [5-DOF Robotic Arm Pick & Place](https://github.com/bipashadeka/ROS2-robo-arm-pick-place) | Designed the arm and a two-finger gripper in SolidWorks, converted it to URDF and used MRAC for a 10-stage pick-and-place in Gazebo. Tracking RMSE of 0.008 to 0.038 rad on the main joints. | ROS2, Gazebo, ros2_control, Python |
| [Quadruped Robot](https://github.com/bipashadeka/quadruped-cad-model-analysis) | Al 6061 body with four 2-DOF legs. Wrote the inverse kinematics and a trot gait in Python (80 mm stride, 0.8 s cycle). Stability margin of 100 mm. | SolidWorks, Python |
| [Industrial Robotic Gripper](https://github.com/bipashadeka/Industrial_Gripper_) | Rack-and-pinion parallel gripper. Did a motion study and a static stress study on it. | SolidWorks Simulation |
| [Robotic Arm Link FEA](https://github.com/bipashadeka/robotic-arm-link-fea-ansys) | Static structural FEA of PLA links. Reactions came within 0.12% of my hand calcs. | ANSYS, Python |
| [IoT Weather Station](https://github.com/bipashadeka/IoT_Weather_Station) | Monitors temperature and humidity in real time. | C++, sensors |

---

### Tools

**CAD & Simulation**

![SolidWorks](https://img.shields.io/badge/SOLIDWORKS-e75480?style=for-the-badge&logo=dassaultsystemes&logoColor=white)
![SOLIDWORKS Simulation](https://img.shields.io/badge/SOLIDWORKS_Simulation-e75480?style=for-the-badge&logo=dassaultsystemes&logoColor=white)
![ANSYS](https://img.shields.io/badge/ANSYS_Workbench-e75480?style=for-the-badge&logo=ansys&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-e75480?style=for-the-badge&logo=mathworks&logoColor=white)

**Robotics & Programming**

![ROS2](https://img.shields.io/badge/ROS2_Jazzy-9c2f5e?style=for-the-badge&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo_Harmonic-9c2f5e?style=for-the-badge&logo=gazebo&logoColor=white)
![RViz2](https://img.shields.io/badge/RViz2-9c2f5e?style=for-the-badge&logo=ros&logoColor=white)
![URDF](https://img.shields.io/badge/URDF-9c2f5e?style=for-the-badge&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-9c2f5e?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-9c2f5e?style=for-the-badge&logo=cplusplus&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-9c2f5e?style=for-the-badge&logo=numpy&logoColor=white)
![Git](https://img.shields.io/badge/Git-9c2f5e?style=for-the-badge&logo=git&logoColor=white)

---

### Experience

**Industrial Intern, IOCL Guwahati Refinery** (Jun to Jul 2026)<br>
Studied maintenance of static and rotary equipment like pumps, heat exchangers, furnaces and pressure vessels.

**Industrial Intern, Diesel Loco Shed, NF Railway, Guwahati** (Jun to Jul 2025)<br>
Worked on ALCO/HHP fuel injection pumps and mechanical unit injectors: inspection, overhauling, calibration and failure analysis.

---

### Activity

<p align="center">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="profile-3d-contrib/profile-night-rainbow.svg" />
<img src="profile-3d-contrib/profile-season-animate.svg" alt="3D contribution graph" width="100%" />
</picture>
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=bipashadeka&bg_color=00000000&color=e75480&line=e75480&point=f08cb4&area=true&area_color=e75480&hide_border=true&title_color=e75480&custom_title=Contributions" width="100%" />
</p>

<p align="center">
<img src="https://streak-stats.demolab.com?user=bipashadeka&hide_border=true&background=00000000&ring=e75480&fire=e75480&currStrNum=e75480&currStrLabel=e75480&sideNums=8b949e&sideLabels=8b949e&dates=8b949e&stroke=8b949e40" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:e75480,50:f08cb4,100:ffd1e8&height=120&section=footer&animation=twinkling" width="100%"/>
