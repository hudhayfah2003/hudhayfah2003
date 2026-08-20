# Huthaifa Foudeh

Final-year Mechanical Engineering student at Jordan University of Science and Technology, working on autonomous mobile robots across the full stack — mechanical design, drivetrain and power electronics, embedded control, and ROS 2.

I build hardware and I debug it. Most of what is here is documented from real machines, not tutorials.

**Graduating February 2027.** Looking for hands-on robotics / autonomous systems / R&D work.

---

### What I've built

**[Tracked Robotic Platform — 350 kg payload class](https://github.com/hudhayfah2003/apl-tracked-platform)**
A four-corner tracked ground platform at the Autonomous Platforms Lab, JUST. I designed the chassis around standard steel tube stock, paired salvaged hoverboard hub motors back-to-back to double drive torque, CNC-machined the sprockets that carry the tracks, built the wiring harness by hand, and validated joystick differential mixing on a low-power LED rig before energising the drivetrain. Halted when funding ended — the built work and the unbuilt plan are documented separately.

**[Autonomous Four-Wheeled Vehicle](https://github.com/hudhayfah2003/rover-ws)** — graduation project
ROS 2 Jazzy and Gazebo Harmonic simulation workspace. Environment bring-up and a YAML-configured `ros_gz_bridge` translating `/cmd_vel` between ROS 2 and Gazebo, verified by teleoperation. Reinforcement learning control in PyTorch is next.

**[Gazebo Harmonic — gz-transport discovery fix](https://github.com/hudhayfah2003/gazebo-gz-transport-fix)**
Gazebo froze on startup with every symptom pointing at the GPU. It was UDP multicast discovery failing on the loopback interface. Root-caused from the transport log, fixed, and automated as a systemd unit. Written up because the problem is common and the documentation is not.

**[Servo bracket — dual-support mount](https://github.com/hudhayfah2003/servo-bracket-dual-support)**
A printed bracket that adds a second pivot opposite a servo's output shaft, taking the bending moment off the gearbox. Four parts, no fasteners: a slide-in arc retains the shaft and a wedge locks it.

**[Cookie vending machine controller](https://github.com/hudhayfah2003/digital-logic-cost-optimization)**
K-map minimisation, then five realisation strategies costed against real IC prices. Three of them need the same package count — only per-family costing finds the cheapest build.

---

### Tools

`ROS 2 Jazzy` · `Gazebo Harmonic` · `Python` · `C++` · `PyTorch` · `SolidWorks` · `ESP32` · `Arduino` · `Raspberry Pi` · `Ubuntu` · `Git` · `FDM printing`

### Currently learning

Reinforcement learning for continuous control — PPO, reward shaping, and the gap between a policy that works in simulation and one that survives contact with hardware.

---

📍Saudi Arabia · [LinkedIn](https://www.linkedin.com/in/huthaifa-foudeh-1105b5286/)
