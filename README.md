
# GridWorld Reinforcement Learning Project

## Overview

Welcome to the GridWorld Reinforcement Learning project! This repository contains the implementation of a reinforcement learning agent designed to navigate a 5x5 grid environment. The agent aims to reach a goal while avoiding obstacles, leveraging Deep Q-Networks (DQN) for optimal decision-making.

---

## Features

- **GridWorld Environment:** A 5x5 grid with obstacles (cats) and a goal (flower).
- **DQN Agent:** Uses TensorFlow to implement Deep Q-Learning.
- **Interactive Visualization:** Tkinter-based interface displaying the agent's progress with custom images and sound effects.
- **Training Mechanism:** Incorporates replay memory and target network updates for efficient learning.

---

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

- Python 3.x
- TensorFlow
- Tkinter
- Pygame
- Numpy
- Pillow

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/GridWorldRL.git
cd GridWorldRL
```

Install the required libraries:

```bash
pip install tensorflow pygame numpy pillow
```

### Running the Project

Execute the main script to start the GridWorld simulation:

```bash
python main.py
```

---

## Project Structure

- **main.py:** The main script to run the GridWorld simulation.
- **GridWorld.py:** Contains the GridWorld environment class.
- **DQNAgent.py:** Contains the DQN agent class.
- **RLVisualizer.py:** Contains the visualization class using Tkinter.

---

## Technical Details

### GridWorld Environment

A 5x5 grid where the bee (agent) starts from the top-left corner and aims to reach the bottom-right corner (goal) while avoiding cats (obstacles).

### DQN Agent

Implemented using TensorFlow, the agent uses a neural network to predict the best actions and learns from its experiences through replay memory and target network updates.

### Visualization

Tkinter is used to create an interactive window showing the bee's movements, with custom images for the bee, flower, and cats. Pygame is used to add sound effects.

---

## Challenges & Learning

- Balancing exploration and exploitation for effective learning.
- Integrating machine learning models with interactive visual elements.
- Handling real-time updates and rendering in Tkinter.

---

## Future Work

- Enhance the complexity of the GridWorld environment.
- Implement more advanced reinforcement learning algorithms.
- Improve the visualization interface for better user experience.

---

## Contributing

Feel free to submit pull requests or report issues to contribute to the project.

---

## License

This project is licensed under the MIT License.
