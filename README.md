# Autonomous UAV Swarm Coordination System

A multi-UAV swarm simulation framework developed using **CoppeliaSim**, **ROS**, and **Python** for autonomous formation control, synchronized coordination, and precision payload deployment.

This project demonstrates cooperative drone swarm behavior using leader-follower architecture, PID-based stabilization, and real-time communication between multiple UAV agents in a simulated environment.

---

# Project Overview

Modern UAV systems are rapidly evolving toward autonomous swarm intelligence for applications such as:

- Surveillance
- Defense systems
- Search & rescue
- Disaster response
- Autonomous coordination
- Precision payload delivery

This project focuses on designing and simulating a coordinated UAV swarm capable of:

- Maintaining geometric formations
- Performing synchronized movement
- Executing autonomous payload release
- Handling communication delays
- Recovering from leader failure scenarios

The entire system was developed and tested inside **CoppeliaSim** with Python-based control logic and ROS experimentation.

---

# Key Features

- Multi-UAV swarm coordination
- Autonomous formation control
- Leader-follower architecture
- Dynamic formation maintenance
- Precision payload deployment
- PID-based flight stabilization
- Communication delay tolerance
- Real-time synchronization
- Swarm scalability experimentation
- Autonomous mission behavior simulation

---

# Technologies Used

| Technology | Purpose |
|---|---|
| CoppeliaSim | UAV simulation environment |
| ROS | Robotics middleware experimentation |
| Python | Swarm coordination and control |
| Lua Scripts | In-simulation drone scripting |
| PID Controllers | Flight stabilization |
| Remote API | Communication between simulator and controller |

---

# Simulation Platforms Explored

During development, multiple UAV simulation environments were explored and tested:

- Gazebo + ROS
- ArduPilot
- Microsoft AirSim
- Webots
- CoppeliaSim

After extensive experimentation and compatibility testing, **CoppeliaSim + Python-based coordination** provided the most stable implementation for swarm simulation.

---

# System Architecture

The system follows a **leader-follower swarm architecture**:

- One UAV acts as the leader
- Follower drones maintain fixed spatial offsets
- Formation updates occur dynamically in real-time
- Communication signals synchronize swarm movement
- PID controllers stabilize motion and orientation

---

# Core Functionalities

## Formation Control

The UAV swarm can maintain coordinated formations such as:

- Square formation
- Line formation
- Dynamic coordinated movement

Formation logic is implemented using positional offsets relative to the leader UAV.

---

## Payload Deployment

Each UAV includes a simulated payload release mechanism capable of:

- Target-based deployment
- Sensor-triggered release
- Coordinated synchronized actions

---

## Communication & Synchronization

The project simulates:

- Inter-drone communication
- Latency handling
- Synchronization delays
- Real-time control propagation

The system remains stable under moderate communication delays.

---

# Performance Highlights

| Metric | Result |
|---|---|
| Formation Stability | Stable coordinated movement |
| Payload Accuracy | ~92% successful deployment |
| Latency Tolerance | Up to 300ms |
| Leader Recovery | Successful swarm reformation |
| Real-Time Response | Low control delay |

---

# Challenges Faced

During development, several engineering challenges were encountered:

- ROS version compatibility issues
- AirSim plugin integration problems
- Multi-agent synchronization complexity
- PID tuning for stable flight
- Communication delay handling
- Real-time simulation coordination
- Swarm scalability limitations

These challenges helped improve understanding of UAV systems, robotics middleware, and distributed autonomous coordination.

---

# Future Improvements

Planned future enhancements include:

- PX4 integration
- MAVLink communication
- Obstacle avoidance
- Vision-based navigation
- Decentralized swarm intelligence
- Hardware deployment using Pixhawk/Raspberry Pi
- Real-world UAV testing
- Advanced controllers (MPC/LQR)

---

# Repository Contents

```text
.
├── Robotics_report.pdf
├── UAV swarms.pptx
├── demoVideo.mp4
├── image1.png
├── image2.png
└── README.md
```

---

# Demonstration

## Demo Video

The repository includes a simulation demo video showcasing:

- Autonomous swarm movement
- Formation coordination
- Multi-UAV synchronization
- Payload deployment behavior

---

# Screenshots

## UAV Swarm Simulation Environment

Add screenshots below:

### Formation Coordination
![Formation](image1.png)

### Multi-UAV Swarm Simulation
![Swarm](image2.png)

---

# Academic Report

The repository also includes:

- Complete project report
- Technical implementation details
- Control algorithms
- System design
- Experimental observations
- Performance evaluation

File:
- `Robotics_report.pdf`

---

# Presentation

Project presentation slides are included in:

- `UAV swarms.pptx`

---

# Applications

Potential real-world applications include:

- Defense and surveillance
- Disaster response systems
- Autonomous reconnaissance
- Coordinated delivery systems
- Search and rescue missions
- Smart autonomous aerial systems

---

# Contributors

- Mukund Thakur
- Sahil Kaushik
- Satyendra Kumar Tandan

Under the guidance of:
- Dr. Shri Vishal Tripathi

Department of Electronics and Communication Engineering  
IIIT Naya Raipur

---

# Disclaimer

This project is developed purely for academic research, simulation, and educational purposes.

---

# License

This repository is intended for educational and research demonstration purposes.
