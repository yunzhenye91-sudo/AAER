# AAER

## Adaptive Robot Swarms with Attentive Adversarial Experience Replay

**Project showcase:** Yunzhen Ye, in collaboration with Jiaping Xiao  
**Research group:** Intelligent Cybernetics Lab, Nanyang Technological University, Singapore  
**Supervisor:** Prof. Mir Feroskhan  
**Publication status:** Manuscript under review at *Nature Communications*

## Algorithm Framework

<!-- Insert the AAER algorithm architecture figure here. -->

## Overview

AAER is a multi-agent reinforcement learning framework for robot swarms in cluttered pursuit–evasion environments. It combines experience from historical opponents with attention to the current scene, enabling robot teams to coordinate their actions while responding to teammates, adversaries, and obstacles.

The framework integrates three components:

- **Historical opponent policy pools:** Previous opponent policies are retained and sampled to generate fresh interactions during training.
- **Entity attention:** Each agent encodes the relative states and roles of teammates, opponents, obstacles, and the target to guide its decisions.
- **Alternating adversarial training:** Pursuers and evaders are trained alternately using PPO, with each team learning against sampled historical opponents.

We evaluate AAER in 5v5 simulation scenarios and demonstrate learned behaviors on physical multi-UAV systems.

## Simulation Experiments

The following videos present selected pursuit–evasion experiments across three environments.

### Room 1

<!-- Insert the Room 1 simulation video here. -->

### Room 2

<!-- Insert the Room 2 simulation video here. -->

### Forest

<!-- Insert the Forest simulation video here. -->

## Real-World Demonstrations

The following three clips show selected portions of our physical multi-UAV experiments, illustrating coordinated pursuit, interception, and obstacle avoidance.

**Only part of the experimental footage is presented here.**

### Clip 1

<!-- Insert the first real-world experiment clip here. -->

### Clip 2

<!-- Insert the second real-world experiment clip here. -->

### Clip 3

<!-- Insert the third real-world experiment clip here. -->

## Planned Releases

This repository currently serves as a project showcase. Additional research materials will be released progressively:

- [ ] Trained models and policy checkpoints
- [ ] Training, evaluation, and deployment code
- [ ] Unity environments and asset packages

More materials and demonstrations will be added as they become available.
