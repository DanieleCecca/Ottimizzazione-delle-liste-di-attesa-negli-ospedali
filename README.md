# \# Optimizing Hospital Waiting Lists with Reinforcement Learning

# 

# This project investigates the use of \*\*Reinforcement Learning (RL)\*\* to optimize hospital waiting list management, a challenging problem characterized by limited resources, stochastic patient arrivals, and progressive clinical deterioration.

# 

# \## Overview

# The scheduling problem is formulated as a \*\*Markov Decision Process (MDP)\*\* where an agent selects, at each step, which patient to schedule. The goal is to balance:

# \- minimization of clinical risk,

# \- compliance with waiting-time constraints (SLAs),

# \- efficient utilization of hospital capacity.

# 

# \## Methods

# The following approaches are compared:

# \- \*\*Maskable Proximal Policy Optimization (PPO)\*\*

# \- \*\*Deep Q-Learning (DQN)\*\*

# 

# against two baselines:

# \- \*\*FIFO (First-In-First-Out)\*\*

# \- \*\*Top-K heuristic\*\*

# 

# \## Results

# \- \*\*PPO\*\* achieves the lowest cumulative clinical risk but produces more late patients.

# \- \*\*DQN\*\* significantly reduces SLA violations at the cost of higher risk accumulation.

# \- Both RL methods outperform static scheduling strategies.

# 

# \## Repository Contents

# \- Hospital waiting list simulation environment

# \- RL agent implementations

# \- Training and evaluation scripts

# \- Episode-level and day-level performance analysis

# 

# \## Notes

# This repository serves as an experimental testbed demonstrating the potential of reinforcement learning for adaptive and clinically motivated hospital scheduling.

# 

