# **BSS_SPACESOLVER**

![LOGO_GIT](https://github.com/user-attachments/assets/b79b4823-adde-43e7-b992-5246f54b0f40)


**BSS_SPACESOLVER** is a gravity and Multiple Gravity Assist (MGA) solver developed using Autodesk Bifrost.  
It is designed for simulating planetary interactions, orbital mechanics, and interplanetary navigation, with a focus on modularity and extendibility.

Example Bifrost graphs are included to help users get started quickly.

---

## Features

- **Gravity Solver**  
  Supports N-body dynamics and planetary gravitational interactions.  

https://github.com/user-attachments/assets/b2cb7a2c-0e94-4b33-b6b5-3277626d58e7

- **Mega Meter Unit System**  
  Uses a scalable unit system to prevent floating-point precision issues common at astronomical scales.

- **Orbit-Based Planet Configuration**  
  Simplifies the creation of known solar systems through orbital parameters.

- **Satellite Honing System**  
  Enables simulation of docking and close-approach maneuvers.

- **MGA Trajectory Solver**  
  Calculates gravity-assisted trajectories for efficient space travel. Based on https://www.sciencedirect.com/science/article/abs/pii/S0094576513001938?via%3Dihub

https://github.com/user-attachments/assets/5391c188-97b9-4820-a6b8-dadd0ca0f09e


- **Custom Planet Integration**  
  Planets can be easily added and configured to fit specific use cases.

- **Viewport 2.0 Visualization**  
  Supports in-viewport visualization with adjustable simulation speed for intuitive debugging and analysis.

- **Node-Based Design**  
  Built entirely using Bifrost compounds for modular, visual programming and rapid iteration.

---

## Work in Progress

- Expanded technical documentation
- Improved satellite honing system with PID-based control
- User interface enhancements
- Runge-Kutta 4th order integration
- Input/output support for file-based persistence

---

## Tested Environment

- **Autodesk Maya 2025**
- **Bifrost 2.12**
- Utilizes **Bullet** and **MJCG** compound libraries

---

## Documentation

Full documentation is available here:  
[Project Documentation (Google Docs)](https://docs.google.com/document/d/1eyCw9Prfol-1i7ISe89SDRa-YdKlKO4XuGbKqBad85s/edit?usp=sharing)
