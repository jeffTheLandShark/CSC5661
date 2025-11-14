# CSC5661 - Reinforcement Learning
## Overview

This repository contains my work from the **CSC5661 - Reinforcement Learning** class at the Milwaukee School of Engineering (Fall 2025), instructed by Dr. Jeremy Kedziora. 
The course focuses on the fundamentals of reinforcement learning (RL), including key concepts, mathematics, algorithms, and applications of RL.

## Learning Objectives

The following course objectives were provided by the course syllabus:

- Define key features of RL that distinguish it from other forms of machine learning;
- Take a given substantive problem (e.g. from computer vision, robotics, etc), decide if it should be formulated as a RL problem and, if yes, define it formally (in terms of the state space, action space, dynamics, and reward model) and determine what algorithm (from class) is best suited for addressing it;
- Implement environmental simulators capable of generating the data needed to train an RL agent in python;
- Implement the common RL algorithms and their underlying component processes in python;
- Describe (list and define) multiple criteria for analyzing RL algorithms and evaluate algorithms on these metrics: e.g. regret, sample complexity, computational complexity, empirical performance, convergence, etc;
- Describe the exploration vs exploitation challenge and compare and contrast at least two approaches for addressing this challenge (in terms of performance, scalability, complexity of implementation, and theoretical guarantees).

## Repository Structure

The files in this repository are organized into the following categories:

```shell
├── ref/         # reference materials and documentation
└── labs/        # class labs 
```

### Labs

| Lab                             | Description                                                                                         |
|---------------------------------|-----------------------------------------------------------------------------------------------------|
| `labs/lab01-bandits`            | Implementation and analysis of contextual multi-armed bandit algorithm.                             |
| `labs/lab02-environment`        | Implementationa and analysis of two simple custom RL environments.                                  |
| `labs/lab03-classical`          | Implementation and analysis of SARSA and Monte Carlo RL algorithms in custom racetrack environment. |
| `labs/lab04-classical_v_moderm` | Implementation and analysis of Q-Learning and DQN algorithms in custom battleship environment.      |

## Tools and Technologies

- **Languages**: Python
- **Libraries**: NumPy, Pandas, Jupyter


## Academic Honesty

This repository is published to showcase my work and document my learning progress throughout the course. If you are a student in the same course, please be aware of your academic institution's policies on academic honesty and integrity. **Do not copy any part of these assignments for your own submission.**
