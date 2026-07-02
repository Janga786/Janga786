# Jangara Bliss

Computer engineering student at Fort Lewis College working in robotics and embodied AI — currently deploying vision-language navigation on a real humanoid robot.

**Portfolio: [janga786.github.io](https://janga786.github.io)** · [jangarabliss@gmail.com](mailto:jangarabliss@gmail.com)

## Current research — humanoid vision-language navigation

I work with the Booster K1 humanoid, taking the NaVILA vision-language-action model from simulation to real hardware:

- A velocity-tracking PPO locomotion policy driven by an 8B VLA model in MuJoCo — physical walking (not sliding) toward natural-language navigation goals, with multi-step instructions and heading assist
- VLN-CE benchmark evaluation and a sim-to-real deployment bridge built on the Booster SDK
- Reactive visual servoing on the real robot: detect a target object and walk to a fixed standoff

Research code lives in private repositories for now; demo videos and a write-up are on my [portfolio](https://janga786.github.io).

## Featured projects

### Robotics & perception

| Project | What it is |
| --- | --- |
| [hexapod-cpg](https://github.com/Janga786/hexapod-cpg) | Custom 18-DoF hexapod robot — Kuramoto-CPG locomotion controller, IMU heading-hold autonomous firmware, full mechanical CAD, 34-test verification suite |
| [kuka-kr6-kinematics](https://github.com/Janga786/kuka-kr6-kinematics) | From-scratch forward/inverse kinematics, geometric Jacobian, singularity diagnostics, and trajectory planning for the KUKA KR 6 R900 — 39-test suite |
| [lidar-pointcloud-motion-pipeline](https://github.com/Janga786/lidar-pointcloud-motion-pipeline) | Open3D + NumPy point-cloud motion analysis: PCA orientation, frame-pair motion detection, ICP rotation-rate estimation |
| [CV-YOLO-Inspection](https://github.com/Janga786/CV-YOLO-Inspection) | Synthetic-data inspection pipeline — Blender-rendered training data, YOLO11 detection, autoencoder anomaly detection |
| [robot_vision](https://github.com/Janga786/robot_vision) | Synthetic labeled training data from a single photogrammetry scan — Blender domain randomization into YOLO training |

### Embedded systems & hardware

| Project | What it is |
| --- | --- |
| [basys3-fpga-portfolio](https://github.com/Janga786/basys3-fpga-portfolio) | Six Verilog systems on the Artix-7: PicoBlaze + OLED, XADC SPI bridge, PS/2-to-UART stack, soft-core CPU, FSMs |
| [arduino-mega-microcontrollers](https://github.com/Janga786/arduino-mega-microcontrollers) | Custom ATmega2560 PCB with production Gerbers, bare-metal 40 kHz ADC sampling, a hand-built IR link-layer protocol |
| [cmos-vlsi-spice-portfolio](https://github.com/Janga786/cmos-vlsi-spice-portfolio) | Transistor-level CMOS design in 0.6 µm SCMOS: 8-bit ALU, R-2R DAC + flash ADC, transmission-gate MUX, full gate library |

### Software

| Project | What it is |
| --- | --- |
| [cpp-algorithms-portfolio](https://github.com/Janga786/cpp-algorithms-portfolio) | Six classical CS algorithms in clean, self-contained C++17 — union-find, MST, Huffman, optimal BST DP |
| [pacman-pygame](https://github.com/Janga786/pacman-pygame) | A complete Pac-Man clone in 443 lines of Pygame — four ghosts with target-chasing AI, power pellets, level state machine |

Also building Basecamp, a mobile-first training/habits PWA (React + TypeScript + Vite, swappable localStorage/Supabase backend, Google Health API sync) — private repo.

Also: member of Fort Lewis College's NASA Rover Challenge team (mechanical + software).

## Toolbox

Python · C/C++ · ROS 1/2 · PyTorch · MuJoCo · Isaac Sim · OpenCV · Verilog · EAGLE/KiCad · Docker
