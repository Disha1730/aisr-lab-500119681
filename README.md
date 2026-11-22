# Artificial Intelligence in Smart Robotics (CSAI4014) — Laboratory Repository

**Student Name:** Disha Rastogi  
**SAP ID:** 500119681
**Roll Number:** R2142230242 
**Batch:** B.Tech CSE (AI & ML) B1  
**Course Teacher:** Dr. Resham Raj Shivwanshi  

---

## Experiments Overview

| Experiment No. | Experiment Title / Name | Purpose / What It Is For |
| :--- | :--- | :--- |
| **Experiment 1** | **Signal Processing and Pendulum Dynamics** | Constructs composite multi-frequency signals to study discrete Fourier spectral analysis (DFT/FFT), proves Shannon-Nyquist aliasing under sub-Nyquist sampling, and simulates nonlinear damped pendulum dynamics via numerical ODE integration to examine phase-space portraits and period elongation. |
| **Experiment 2** | **Constraint Satisfaction and Backtracking — N-Queens** | Models the $N$-Queens placement problem as a formal Constraint Satisfaction Problem (CSP) over discrete permutation spaces, comparing brute-force factorial generate-and-test against recursive depth-first backtracking with early subtree pruning and constraint propagation. |
| **Experiment 3** | **Grid-World Graph Search — BFS vs. DFS Maze Navigation** | Formulates discrete 2D grid labyrinth traversal as an implicit graph search problem, comparing Breadth-First Search (BFS) and Depth-First Search (DFS) on optimality guarantees, node expansions, and queue/stack frontier memory footprint. |
| **Experiment 4** | **Local Search and Optimisation — Hill Climbing with Restarts** | Analyzes greedy local optimization failure modes on non-convex, multimodal landscapes (local maxima, ridges, plateaus) using 8-Queens, and demonstrates how random restarts restore completeness, validating the binomial success model $P(k) = 1 - (1 - p)^k$. |
| **Experiment 5** | **Reinforcement Learning — Tabular Q-Learning on Gridworld** | Models robot gridworld pathfinding as a Markov Decision Process (MDP) and applies model-free, off-policy tabular Q-learning with temporal difference (TD) updates and an $\varepsilon$-greedy exploration policy to learn an optimal collision-free policy. |
| **Experiment 6** | **Backpropagation and Neural Networks — XOR MLP from Scratch** | Implements a two-layer Multi-Layer Perceptron (2-4-1 MLP) from first principles using pure NumPy to solve the non-linearly separable XOR classification benchmark, analyzing gradient descent dynamics, analytical chain-rule backpropagation, and learning rate sensitivity. |
| **Experiment 7** | **Mobile Robot Simulation in Webots — Reactive Swarm & Lidar Navigation** | Simulates multi-agent robotic navigation in Webots, assessing decentralized emergent obstacle avoidance in e-puck swarms via Braitenberg vehicle cross-connections and evaluating 2D planar lidar Follow-The-Gap (FTG) reactive room navigation on a Pioneer 3-DX platform. |
| **Experiment 8** | **Cross-Embodiment Robot Manipulation — Task-Space Transfer & Behavior Cloning** | Investigates kinematic morphology gaps across heterogeneous manipulators (KUKA iiwa, Franka Panda, xArm6, KUKA mini) in PyBullet, proving why joint-space trajectory transfer fails and demonstrating zero-shot skill transfer using $\mathrm{SE}(3)$ task-space DLS inverse kinematics and behavior cloning policies. |

