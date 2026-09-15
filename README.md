## Muhammad Farhan Suri

Final-year Electrical Engineering student at Universitas Diponegoro, concentrating in
Control and Instrumentation.

I lead **EWS Bascorro**, Diponegoro University's humanoid robot soccer team. Three robots
run ROS 2 — two on Intel NUC computers, one on a Jetson Orin Nano — each with an OpenCR 1.0
board on an STM32F7 handling real-time actuator control. Before leading the team I spent nearly two years working
on its vision and locomotion software: ball detection in OpenCV, leg trajectories from
inverse kinematics, and IMU feedback for balance.

In early 2026 I spent two months at **PT PLN Indonesia Power**, analysing the GE Mark VIe
distributed control system of a 109.65 MW gas turbine generator. The interesting part was
its triple modular redundancy: three controllers run in parallel and vote, and the voted
output follows the median of the three channels rather than the mean, so deviation on one
channel never reaches the control decision.

My final-year project is a pico-hydro generation emulator with battery energy storage,
built so that generating conditions can be reproduced electrically instead of with a water
turbine and a flow rig.

### Selected work

| Repository | What it is |
| --- | --- |
| [system-identification-rls](https://github.com/farhansurii/system-identification-rls) | Recursive online parameter estimation in MATLAB. LMS gradient descent fitting an ARX model to a nonlinear plant, written without the System Identification Toolbox. |
| [dc-microgrid-droop-control](https://github.com/farhansurii/dc-microgrid-droop-control) | Simulink models of two battery units sharing a DC bus through bidirectional converters under droop control, scored with the ITAE index. |
| [arduino-water-level-control](https://github.com/farhansurii/arduino-water-level-control) | Hysteresis pump controller with no external libraries — hand-written bit-banged I²C, an HD44780 LCD driver, and an oversampling filter on the ultrasonic sensor. |
| [Auto_GateToll_simpleVer](https://github.com/farhansurii/Auto_GateToll_simpleVer) | Automated barrier on ESP32 using ultrasonic ranging and servo actuation. |
| [smartdoor_esp](https://github.com/farhansurii/smartdoor_esp) | ESP32 door lock experiment. |

### Working with

- **Control** — PID tuning, state-space modelling, system identification, digital control, droop control
- **Simulation** — MATLAB, Simulink, Stateflow, Webots, Proteus
- **Embedded** — STM32, OpenCR 1.0, Arduino, ESP32, I²C, SPI, UART, RS-485
- **Robotics** — ROS 2, forward and inverse kinematics, trajectory generation, Dynamixel servos
- **Languages** — C, C++, Python, MATLAB

### Contact

[frhnsuri@gmail.com](mailto:frhnsuri@gmail.com) · [LinkedIn](https://linkedin.com/in/muhammadfarhansuri)
