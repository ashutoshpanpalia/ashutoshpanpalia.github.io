# Graph Report - .  (2026-04-30)

## Corpus Check
- 8 files · ~50,000 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 60 nodes · 63 edges · 16 communities detected
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 7 edges (avg confidence: 0.79)
- Token cost: 9,800 input · 3,200 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Career and Affiliations|Career and Affiliations]]
- [[_COMMUNITY_Site Structure and Config|Site Structure and Config]]
- [[_COMMUNITY_RL Locomotion and Navigation|RL Locomotion and Navigation]]
- [[_COMMUNITY_Perception and Robot Manipulation|Perception and Robot Manipulation]]
- [[_COMMUNITY_Classic RL and Control|Classic RL and Control]]
- [[_COMMUNITY_Computer Vision and Detection|Computer Vision and Detection]]
- [[_COMMUNITY_Autonomous Racing|Autonomous Racing]]
- [[_COMMUNITY_Startup Activities|Startup Activities]]
- [[_COMMUNITY_DDPG Locomotion|DDPG Locomotion]]
- [[_COMMUNITY_UB Startup Competition|UB Startup Competition]]
- [[_COMMUNITY_Water Rescue Drone|Water Rescue Drone]]
- [[_COMMUNITY_Mars Rover Arm|Mars Rover Arm]]
- [[_COMMUNITY_Go-Kart Build|Go-Kart Build]]
- [[_COMMUNITY_Manufacturing Experiment|Manufacturing Experiment]]
- [[_COMMUNITY_PyTorch|PyTorch]]
- [[_COMMUNITY_Python|Python]]

## God Nodes (most connected - your core abstractions)
1. `Homepage (index.html)` - 11 edges
2. `Ashutosh Panpalia` - 7 edges
3. `Projects Page (projects.html)` - 5 edges
4. `Portfolio CLAUDE.md Project Config` - 5 edges
5. `Style Sheet (css/style.css)` - 5 edges
6. `Main JavaScript (js/main.js)` - 5 edges
7. `Mini Projects Page (fun.html)` - 4 edges
8. `Resume PDF (asset/Ash_resume.pdf)` - 4 edges
9. `RL-Based Locomotion for Unitree Go2 (2025)` - 4 edges
10. `Intel RealSense D405` - 4 edges

## Surprising Connections (you probably didn't know these)
- `About Page (about.html)` --references--> `Main JavaScript (js/main.js)`  [EXTRACTED]
  about.html → js/main.js
- `Custom YOLO Model Training with Synthetic Data (Mini Project)` --semantically_similar_to--> `Synthetic vs Real vs Hybrid Datasets for CAD Object Detection - SyncMfg (2026)`  [INFERRED] [semantically similar]
  fun.html → projects.html
- `RL Agent Learning to Push Objects (Mini Project)` --semantically_similar_to--> `RL-Based Manipulator Control Without Analytical IK - Trossen Arm (2025)`  [INFERRED] [semantically similar]
  fun.html → projects.html
- `Deep Q-Learning for Classic Control - Inverted Pendulum (2024)` --semantically_similar_to--> `RL Inverted Pendulum in Isaac Sim (Mini Project)`  [INFERRED] [semantically similar]
  projects.html → fun.html
- `Homepage (index.html)` --references--> `Main JavaScript (js/main.js)`  [EXTRACTED]
  index.html → js/main.js

## Hyperedges (group relationships)
- **Reinforcement Learning Locomotion Pipeline** — project_unitreego2_rl_2025, project_unitreego2_stairs_2026, project_sim2sim_2025, tech_isaaclab [EXTRACTED 0.95]
- **Robot Manipulation Learning Cluster** — project_diffusionpolicy_2026, project_trossenarm_2025, project_linearslip_2025, project_rotslip_2025 [INFERRED 0.82]
- **Perception and Vision Pipeline Cluster** — project_foundationpose_2026, project_visualservoing_2026, tech_realsense, tech_foundationpose [INFERRED 0.88]

## Communities

### Community 0 - "Career and Affiliations"
Cohesion: 0.22
Nodes (11): Hero MotoCorp Ltd., IIT Kanpur, University at Buffalo, ZOHO (Texas), Ashutosh Panpalia, System Identification on FANUC Industrial Robot - IIT Kanpur (2023 and earlier), Manufacturing Quality Improvement Award - Hero MotoCorp (2023 and earlier), Linear Slip Mitigation in Robotic Manipulation - Nature Communications (2025) (+3 more)

### Community 1 - "Site Structure and Config"
Cohesion: 0.53
Nodes (9): About Page (about.html), Resume PDF (asset/Ash_resume.pdf), Portfolio CLAUDE.md Project Config, Style Sheet (css/style.css), Mini Projects Page (fun.html), GitHub Pages Hosting, Homepage (index.html), Main JavaScript (js/main.js) (+1 more)

### Community 2 - "RL Locomotion and Navigation"
Cohesion: 0.28
Nodes (9): ORB-SLAM Implementation (Mini Project), ROS 2 Navigation Stack Deployment in Isaac Sim (2025), Sim-to-Sim RL Policy Transfer Isaac Lab to Isaac Sim (2025), RL-Based Locomotion for Unitree Go2 (2025), Robust RL Locomotion for Unitree Go2: Terrain Adaptation & Stair Climbing (2026), NVIDIA Isaac Lab, NVIDIA Isaac Sim, ROS 2 (+1 more)

### Community 3 - "Perception and Robot Manipulation"
Cohesion: 0.29
Nodes (7): Intel RealSense vs Kinect Depth Comparison (Mini Project), Diffusion Policy Training for Manipulation (2026), 6DoF Object Pose Estimation with FoundationPose (2026), Visual Servoing with Ufactory Arm and AprilTag Tracking (2026), Diffusion Policy, NVIDIA FoundationPose, Intel RealSense D405

### Community 4 - "Classic RL and Control"
Cohesion: 0.4
Nodes (5): RL Inverted Pendulum in Isaac Sim (Mini Project), RL Agent Learning to Push Objects (Mini Project), Deep Q-Learning for Classic Control - Inverted Pendulum (2024), RL-Based Manipulator Control Without Analytical IK - Trossen Arm (2025), PyBullet

### Community 5 - "Computer Vision and Detection"
Cohesion: 0.5
Nodes (5): Custom YOLO Model Training with Synthetic Data (Mini Project), 3D Citrus Fruit Detection and Size Estimation (2025), Synthetic vs Real vs Hybrid Datasets for CAD Object Detection - SyncMfg (2026), OpenCV, YOLO Object Detection

### Community 7 - "Autonomous Racing"
Cohesion: 1.0
Nodes (2): Autonomous Driving Control on F1TENTH Using PID and Gap Follow (2024), Dynamic Obstacle Avoidance Using RRT on F1TENTH (2024)

### Community 8 - "Startup Activities"
Cohesion: 1.0
Nodes (1): Startup Judge - Startup Texas Pitch & SBIR/STTR Demo Day (2025)

### Community 9 - "DDPG Locomotion"
Cohesion: 1.0
Nodes (1): Continuous Control with DDPG for Bipedal Locomotion (2024)

### Community 10 - "UB Startup Competition"
Cohesion: 1.0
Nodes (1): Startup Competition Participant - Panasci UB (2024)

### Community 11 - "Water Rescue Drone"
Cohesion: 1.0
Nodes (1): Water Rescue Drone for Drowning Rescue Assistance (2023 and earlier)

### Community 12 - "Mars Rover Arm"
Cohesion: 1.0
Nodes (1): Modular Robotic Arm for Mars Rover 5-DOF (2023 and earlier)

### Community 13 - "Go-Kart Build"
Cohesion: 1.0
Nodes (1): Go-Kart Design and Build Project (2023 and earlier)

### Community 14 - "Manufacturing Experiment"
Cohesion: 1.0
Nodes (1): Slow-Motion Metal Chip Formation Experiment (Mini Project)

### Community 15 - "PyTorch"
Cohesion: 1.0
Nodes (1): PyTorch

### Community 16 - "Python"
Cohesion: 1.0
Nodes (1): Python

## Knowledge Gaps
- **25 isolated node(s):** `Visual Servoing with Ufactory Arm and AprilTag Tracking (2026)`, `Startup Judge - Startup Texas Pitch & SBIR/STTR Demo Day (2025)`, `Deep Q-Learning for Classic Control - Inverted Pendulum (2024)`, `Continuous Control with DDPG for Bipedal Locomotion (2024)`, `Autonomous Driving Control on F1TENTH Using PID and Gap Follow (2024)` (+20 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Autonomous Racing`** (2 nodes): `Autonomous Driving Control on F1TENTH Using PID and Gap Follow (2024)`, `Dynamic Obstacle Avoidance Using RRT on F1TENTH (2024)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Startup Activities`** (1 nodes): `Startup Judge - Startup Texas Pitch & SBIR/STTR Demo Day (2025)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `DDPG Locomotion`** (1 nodes): `Continuous Control with DDPG for Bipedal Locomotion (2024)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `UB Startup Competition`** (1 nodes): `Startup Competition Participant - Panasci UB (2024)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Water Rescue Drone`** (1 nodes): `Water Rescue Drone for Drowning Rescue Assistance (2023 and earlier)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Mars Rover Arm`** (1 nodes): `Modular Robotic Arm for Mars Rover 5-DOF (2023 and earlier)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Go-Kart Build`** (1 nodes): `Go-Kart Design and Build Project (2023 and earlier)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Manufacturing Experiment`** (1 nodes): `Slow-Motion Metal Chip Formation Experiment (Mini Project)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `PyTorch`** (1 nodes): `PyTorch`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Python`** (1 nodes): `Python`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Homepage (index.html)` connect `Site Structure and Config` to `Career and Affiliations`, `RL Locomotion and Navigation`, `Classic RL and Control`, `Computer Vision and Detection`?**
  _High betweenness centrality (0.335) - this node is a cross-community bridge._
- **Why does `Ashutosh Panpalia` connect `Career and Affiliations` to `Site Structure and Config`?**
  _High betweenness centrality (0.185) - this node is a cross-community bridge._
- **Why does `RL-Based Locomotion for Unitree Go2 (2025)` connect `RL Locomotion and Navigation` to `Site Structure and Config`?**
  _High betweenness centrality (0.142) - this node is a cross-community bridge._
- **What connects `Visual Servoing with Ufactory Arm and AprilTag Tracking (2026)`, `Startup Judge - Startup Texas Pitch & SBIR/STTR Demo Day (2025)`, `Deep Q-Learning for Classic Control - Inverted Pendulum (2024)` to the rest of the system?**
  _25 weakly-connected nodes found - possible documentation gaps or missing edges._