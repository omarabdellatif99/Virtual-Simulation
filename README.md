# Training a Virtual JetRacer within Unreal Engine 5: Simulating Real-World Racing
 Track Lighting Conditions for Autonomous Navigation ( Ongoing project )
## Overview

This project focuses on creating a **high-fidelity, photorealistic simulation environment** within **Unreal Engine 5** to train and test autonomous systems, specifically **virtual JetRacers**, under varied and challenging lighting conditions. The simulation replicates real-world environments, from direct sunlight to low-light and night driving scenarios, allowing autonomous systems to be exposed to a wide range of lighting conditions. The research aims to explore the effectiveness of synthetic data generated from these simulations in training machine learning models and determining whether photorealistic simulations can replace physical testing in autonomous vehicle development.

## Key Features

- **Realistic Lighting Scenarios**: 
  The environment in Unreal Engine 5 includes a variety of lighting conditions, including direct sunlight, overcast skies, dusk, and nighttime, to simulate the diverse and challenging conditions that autonomous vehicles might encounter in the real world.

- **Virtual JetRacer Simulation**: 
  Virtual JetRacers are used as the autonomous systems for this study. These JetRacers navigate the environment and react to changing lighting and visibility conditions, making them an ideal platform for testing autonomous systems in different environments.

- **Unreal Engine 5 Technology**: 
  Leveraging the advanced features of **Unreal Engine 5**, such as **photorealistic graphics**, **dynamic lighting**, and **Blueprints**, this project creates a visually accurate and immersive simulation environment. The engine’s capabilities allow for smooth transitions between different lighting scenarios and provide a realistic representation of how light affects the environment and the performance of autonomous systems.

- **Machine Learning Integration**: 
  This simulation generates **synthetic data** to train machine learning models for autonomous driving. The models are trained to adapt to real-world challenges by learning from the photorealistic simulation data, enabling a comparison with real-world data performance.

- **Dynamic Pathfinding and Navigation**: 
  Using Unreal Engine’s **Blueprints** and **Python API** integration, the JetRacers are trained to follow specific paths within the simulation. The camera system adapts in real-time, mimicking the behavior of real-world autonomous systems, as it relies on machine learning models for guidance.

## Research Goals

- **Simulate Real-World Lighting Conditions**: 
  Build a dynamic simulation environment with various lighting conditions to expose virtual JetRacers to different scenarios, such as bright daylight, sunset, and night driving.
  
- **Assess Synthetic Data for Machine Learning**: 
  Investigate the impact of synthetic simulation data on the performance of machine learning models, comparing the results with models trained using real-world data to assess the viability of simulation-based training.
  
- **Evaluate the Response of Autonomous Systems**: 
  Analyze how virtual JetRacers adapt to different lighting environments and visibility changes, focusing on how these systems interpret and respond to varying levels of light.

## Getting Started

To run this project on your machine, follow the steps below:

### Prerequisites

1. **Unreal Engine 5**: Download and install Unreal Engine 5 from the [Epic Games Launcher](https://www.unrealengine.com/download).
2. **Python 3.x**: Make sure Python is installed for running scripts and integrating machine learning models with Unreal Engine. Download Python from [python.org](https://www.python.org/downloads/).
3. **PyCharm (optional)**: If you plan on modifying or training machine learning models for integration, PyCharm or another Python IDE can be helpful.



<img width="704" alt="ue55" src="https://github.com/user-attachments/assets/a82473cb-271a-4f07-a083-cf1a844aaba9">

![bpspline](https://github.com/user-attachments/assets/731ca166-f150-47f3-b306-46a9855a2f48)

![spline viewport](https://github.com/user-attachments/assets/00af8279-9471-404e-9b7b-9ed274336045)
