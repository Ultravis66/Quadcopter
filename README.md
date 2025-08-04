# Quadcopter RBM Simulation

This project demonstrates a CFD simulation of a quadcopter using **Rigid Body Motion (RBM)** to model spinning rotors and visualize wake dynamics. 785 rad/sec.

## 🧩 Mesh and Propeller Setup

| Full Assembly with Overset Domains | Detailed View Around a Single Propeller |
|------------------------------------|------------------------------------------|
| ![Overset Mesh](Mesh.png)          | ![Propeller Detail](Prop.png)            |

## Downwake Preview

![Quadcopter View](QuadcopterI.png)


## Simulation Gif

![Quadcopter Wake](Quadcopter.gif)

---

| Force X | Force Y (Lifting) | Force Z |

| ![Force X](ForceX.png) | ![Force Y](ForceY.png) | ![Force Z](ForceZ.png) |

### Combined Moments

![Moments](Moments.png)

---

## 🧠 Simulation Details

- 4 rotors modeled with RBM (2 CW, 2 CCW)
- Simulated using HPC resources
- Ran on a multi-node Linux-based cluster
- Batch-submitted using SLURM scripting
- Overset mesh for spinning rotor regions
- Wake behavior and stability analysis
