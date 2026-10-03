# Jangara Bliss

Computer engineering student at Fort Lewis College working on robot learning and embodied autonomy: benchmarks, simulation, controls, perception, and the embedded systems underneath them.

**Portfolio: [janga786.github.io](https://janga786.github.io)** · [jangarabliss@gmail.com](mailto:jangarabliss@gmail.com) · [LinkedIn](https://www.linkedin.com/in/jangarabliss/)

## Research and flagship work

| Project | What it is |
| --- | --- |
| [xembench](https://github.com/Janga786/xembench) | Cross-embodiment, language-grounded manipulation benchmark in ManiSkill3: one policy interface, a Franka Panda arm and a Unitree G1 humanoid. 6,550 baseline episodes with Wilson CIs, a data-flywheel round, a documented negative result on precision manipulation, 198 tests |
| [k1-vlm-navigation](https://github.com/Janga786/k1-vlm-navigation) | NaVILA vision-language model driving a velocity-tracking PPO locomotion policy on the Booster K1 humanoid in MuJoCo, with multi-step instructions, heading assist, and a real-robot deploy path (dry-run and live modes, watchdog, 58 unit tests) |
| [k1_checkout_validator](https://github.com/Janga786/k1_checkout_validator) | ROS 2 cart-seek stack for the real K1: YOLO-World detection, odom-frame tracking, and a gated, hard-clamped Booster SDK bridge with a lost-target stop |
| [rebot-crack-vision](https://github.com/Janga786/rebot-crack-vision) | Zero-shot crack segmentation for a reBot B601-DM concrete-inspection arm, spec-driven with decision records. Robot-side work is simulation only so far |

Canonical NaVILA-on-K1 benchmark results (1,077 episodes) are simulation-only. The write-up and evidence ledger are on the [portfolio](https://janga786.github.io). The research workspace stays private.

## Robotics, perception and controls

| Project | What it is |
| --- | --- |
| [hexapod-cpg](https://github.com/Janga786/hexapod-cpg) | Custom 18-DoF hexapod from the NASA Colorado Robotics Challenge: Kuramoto-CPG locomotion, IMU heading-hold firmware, mechanical CAD, 34-test verification suite |
| [kuka-kr6-kinematics](https://github.com/Janga786/kuka-kr6-kinematics) | From-scratch forward/inverse kinematics, geometric Jacobian, singularity diagnostics, and trajectory planning for the KUKA KR 6 R900, with a 39-test suite |
| [lidar-pointcloud-motion-pipeline](https://github.com/Janga786/lidar-pointcloud-motion-pipeline) | Open3D + NumPy point-cloud motion analysis: PCA orientation, frame-pair motion detection, ICP rotation-rate estimation |
| [CV-YOLO-Inspection](https://github.com/Janga786/CV-YOLO-Inspection) | Synthetic-data inspection pipeline: Blender-rendered training data, YOLO11 detection, autoencoder anomaly detection |
| [robot_vision](https://github.com/Janga786/robot_vision) | Synthetic labeled training data from a single photogrammetry scan, using Blender domain randomization into YOLO training |
| [Baxter-Sawyer_Work_Station_Windows](https://github.com/Janga786/Baxter-Sawyer_Work_Station_Windows) | Dockerized ROS 1 Indigo + ROS 2 Humble workstation with ros1_bridge for restoring and developing on Baxter/Sawyer |

## Embedded systems and hardware

| Project | What it is |
| --- | --- |
| [basys3-fpga-portfolio](https://github.com/Janga786/basys3-fpga-portfolio) | Six Verilog systems on the Artix-7: PicoBlaze + OLED, XADC SPI bridge, PS/2-to-UART stack, soft-core CPU, FSMs |
| [arduino-mega-microcontrollers](https://github.com/Janga786/arduino-mega-microcontrollers) | Custom ATmega2560 PCB with production Gerbers, bare-metal 40 kHz ADC sampling, a hand-built IR link-layer protocol |
| [cmos-vlsi-spice-portfolio](https://github.com/Janga786/cmos-vlsi-spice-portfolio) | Transistor-level CMOS design in 0.6 µm SCMOS: 8-bit ALU, R-2R DAC + flash ADC, transmission-gate MUX, full gate library |

## Software

| Project | What it is |
| --- | --- |
| [cpp-algorithms-portfolio](https://github.com/Janga786/cpp-algorithms-portfolio) | Six classical CS algorithms in self-contained C++17: union-find, MST, Huffman, optimal BST DP |
| [basecamp](https://github.com/Janga786/basecamp) | Mobile-first training and habits PWA (React + TypeScript + Vite, swappable localStorage/Supabase backend, Google Health API sync) |
| [pacman-pygame](https://github.com/Janga786/pacman-pygame) | A complete Pac-Man clone in 443 lines of Pygame, with four target-chasing ghosts, power pellets, and a level state machine |

## Experience

- **Research Assistant, humanoid robotics** (Fort Lewis College): integrated the Booster K1 into a vision-language navigation benchmark.
- **Team lead, NASA Colorado Robotics Challenge:** led a four-person team that built and fielded an autonomous 18-DoF hexapod.
- **Research Assistant, AI and robotics** (Fort Lewis College): restored legacy Sawyer and Baxter robots and built synthetic-data and inspection tooling.

## Toolbox

Python · C/C++ · ROS 1/2 · PyTorch · MuJoCo · ManiSkill3 · Isaac Sim · OpenCV · Verilog · EAGLE/KiCad · Docker
