# Group Behaviour: Hunter-Prey Simulation

## Introduction

This project simulates the group behavior of hunters and prey using emergent behavior principles. Developed in Python, the simulation demonstrates how individual actions of agents (hunters and prey) lead to complex group behaviors.
![Gameplay Image](group.gif)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Detailed Code Analysis](#detailed-code-analysis)
  - [Overview](#overview)
  - [Code Structure](#code-structure)
  - [Key Components](#key-components)
  - [Emergent Behavior](#emergent-behavior)
  - [Simulation Dynamics](#simulation-dynamics)
- [Contributors](#contributors)

## Features

- **Emergent Behavior**: Demonstrates complex group behaviors from simple individual rules.
- **Agent-Based Modeling**: Simulates interactions between hunters and prey.
- **Visual Representation**: Graphical display of the simulation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Adnan25z/groupBehaviour-Hunter-Prey-.git

2. Navigate to the project directory:
   ```bash
   cd groupBehaviour-Hunter-Prey-

3. Install the required dependencies

## Usage 
1. Run the simulation:
   ```bash
   python main.py

2. Observe the behaviors and interactions between hunters and prey on the graphical interface.

## Dependencies
- Python 3.x
- Pygame

## Configuration
Adjust the simulation parameters in config.py to change the behavior of the hunters and prey, such as speed, sight range, and interaction rules.

## Detailed Code Analysis
### Overview
The project simulates group behavior through emergent principles, where simple individual rules lead to complex group dynamics. It includes separate classes for hunters, prey, and the environment.

### Code Structure
1. Model Layer: Defines the behavior of individual agents.
2. View Layer: Handles the graphical representation using Pygame.
3. Controller Layer: Manages the simulation flow and agent interactions.

### Key Components
- Hunter Class: Defines behaviors and attributes for hunter agents.
- Prey Class: Defines behaviors and attributes for prey agents.
- Environment Class: Manages the environment and agent interactions.

### Emergent Behavior
Agents follow simple rules such as moving towards prey (for hunters) or fleeing from hunters (for prey). These individual rules lead to emergent group behaviors that can be observed in the simulation.

### Simulation Dynamics
The simulation updates each frame, recalculating agent positions and states based on their interactions and the environment. This creates a dynamic system where the collective behavior emerges from individual actions.

## Contributors
Adnan Zafar
