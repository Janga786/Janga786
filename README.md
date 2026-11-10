# Jangara Bliss

I am a senior in Computer Engineering at Fort Lewis College in Durango, Colorado, graduating May 2027. I work on learned control for humanoid and legged robots, down to the embedded layer that drives the motors.

[Portfolio](https://janga786.github.io) · [LinkedIn](https://www.linkedin.com/in/jangarabliss/) · [jangarabliss@gmail.com](mailto:jangarabliss@gmail.com)

## Selected work

**[k1-navila-research](https://github.com/Janga786/k1-navila-research)**: NaVILA, a vision-language navigation model, commanding a 50 Hz RL walking policy I trained for the Booster K1 humanoid.
I added the K1 to the VLN-CE-Isaac benchmark and ran all 1,077 episodes; pipeline fixes and retraining raised success from under 1% to 18.3% (simulation), and ran a 2,400-episode ablation on evaluation repeatability. NaVILA also ran live on the real K1 for two episodes using Booster's built-in walker; my own policy has only worked in simulation.

**[rebot-crack-vision](https://github.com/Janga786/rebot-crack-vision)**: my senior-design arm (reBot B601-DM) for bridge crack inspection.
Seven motors over CAN in a 200 Hz loop, Jacobian, inverse kinematics and a minimum-jerk planner. A torque test measured 6.6 N·m of elbow gravity load against 2.7 N·m in the URDF; feed-forward and retuned gains cut holding error from 0.04–0.05 rad to 0.005 rad or less on the real arm.

**[hexapod-cpg](https://github.com/Janga786/hexapod-cpg)**: the 18-DoF hexapod my four-person team built for NASA Space Grant's Colorado Robotics Challenge.
I led the team, designed the electrical system and added IMU heading hold to firmware extended from Mark W's open-source design. The repo also has my Kuramoto CPG gait simulator (simulation only).

**[k1_checkout_validator](https://github.com/Janga786/k1_checkout_validator)**: ROS 2 cart-seek stack for the real K1.
YOLO-World finds a cart, the K1 walks to about 1 m from it and circles it to read a QR code, behind a gated, speed-clamped Booster SDK bridge.

**[kuka-kr6-kinematics](https://github.com/Janga786/kuka-kr6-kinematics)**: forward and inverse kinematics, geometric Jacobian, singularity checks and trajectory planning for the KUKA KR 6 R900, written from the geometry and checked against a generated URDF. Built for Intro to Robotics.

## More

Robotics and perception
- [k1-vlm-navigation](https://github.com/Janga786/k1-vlm-navigation): NaVILA driving a PPO walking policy on the K1 in MuJoCo, plus a deploy path for the real robot's built-in walker.
- [xembench](https://github.com/Janga786/xembench): ManiSkill3 study of language-conditioned manipulation on a Panda arm and a Unitree G1 humanoid; 6,550 simulated baseline episodes; transfer is not yet measurable because the baselines score 0% on at least one task in each pair.
- [Baxter-Sawyer_Work_Station_Windows](https://github.com/Janga786/Baxter-Sawyer_Work_Station_Windows): Docker workstation (ROS 1 Indigo + Baxter SDK, ROS 2 Humble + MoveIt 2) from reviving two Rethink robots; the ROS 1/ROS 2 bridge is unfinished.
- [Baxter-Troubleshooting](https://github.com/Janga786/Baxter-Troubleshooting): boot, networking and SDK fixes for keeping Baxter running.
- [robot_vision](https://github.com/Janga786/robot_vision): Blender synthetic training data from one photogrammetry scan, for YOLO detection.
- [CV-YOLO-Inspection](https://github.com/Janga786/CV-YOLO-Inspection): Blender synthetic data, YOLO training and an autoencoder for can inspection (synthetic data only, no held-out evaluation).
- [lidar-pointcloud-motion-pipeline](https://github.com/Janga786/lidar-pointcloud-motion-pipeline): Open3D point-cloud dimensions, orientation and ICP rotation-rate estimation.

Embedded and digital design
- [arduino-mega-microcontrollers](https://github.com/Janga786/arduino-mega-microcontrollers): custom ATmega2560 PCB design (Eagle, Gerbers), register-level 40 kHz ADC sampling, an IR serial link with addressing and checksum.
- [basys3-fpga-portfolio](https://github.com/Janga786/basys3-fpga-portfolio): CE 433 Verilog labs on the Basys 3: PicoBlaze, an XADC serial link, PS/2-to-UART, FSMs, an LCD driver.
- [cmos-vlsi-spice-portfolio](https://github.com/Janga786/cmos-vlsi-spice-portfolio): schematic-level CMOS designs simulated in SPICE (AMI C5, 0.6 µm): 8-bit ALU, mirror-adder ripple adder, ring oscillator; simulation only.
- [Digital-Signal-Processing-Filter](https://github.com/Janga786/Digital-Signal-Processing-Filter): second-order IIR resonator in Python with DTFT analysis.

Software
- [cpp-algorithms-portfolio](https://github.com/Janga786/cpp-algorithms-portfolio): classical algorithms in C++17 (union-find, MST, Huffman, optimal BST).

## Experience

- Research Assistant, Humanoid Robot Intelligence · Dr. Yiyan Li · May 2026 – Aug 2026
- Senior Design, Bridge Crack-Inspection Arm · Dr. Yiyan Li · Sep 2026 – present
- Team Lead, Colorado Robotics Challenge (NASA Space Grant) · Dr. Charles Hakes · Oct 2025 – Apr 2026
- Research Assistant, Computer Vision & Robotics · Dr. Kevin Wedeward · May 2025 – Sep 2025: revived Rethink's Sawyer and Baxter; solar-panel hotspot inspection took 2nd place at the FLC Physics & Engineering Symposium
- Research Assistant, AI & Data · Dr. Matthew Welz · Aug 2024 – Oct 2025: music-library database for the FLC radio station
