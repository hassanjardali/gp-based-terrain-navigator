# Autonomous Navigation in Uneven Terrains Using SGP Local Perception

## Overview
This repository contains the code for our research paper titled "Autonomous Mapless Navigation On Uneven Terrain". We propose a novel method for autonomous navigation in uneven terrains by leveraging a Sparse Gaussian Process (SGP) based local perception model. The SGP model is trained on local ranging observations (pointcloud) to learn the terrain's elevation profile and extract feasible navigation subgoals around the robot. 

A custom cost function ensures the safety of the robot by keeping the robot's roll and pitch angles within specified bounds. This cost function is integral to selecting a subgoal that not only is safe but also efficiently leads the robot to its destination. Our algorithm is designed for real-time operation and has been rigorously tested in both simulated and real-world environments, showcasing superior performance and efficiency compared to existing planners.

## Features
- **Sparse Gaussian Process-Based Local Perception:** Trains on local ranging observations to understand the terrain.
- **Safety-Aware Navigation:** Utilizes a cost function to maintain robot safety through roll and pitch angle constraints.
- **Real-Time Operation:** Optimized for real-time use in uneven and challenging terrains.
- **Extensive Evaluation:** Thoroughly tested in simulation and real-world experiments, demonstrating high efficiency and performance.

### Code wil be released soon. 

[![Watch the video](https://img.youtube.com/vi/-WshttryWQ0/0.jpg)](https://youtu.be/-WshttryWQ0)
