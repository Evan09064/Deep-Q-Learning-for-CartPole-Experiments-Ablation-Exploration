# Deep Q-Learning for CartPole

This repository contains a comprehensive PyTorch implementation of Deep Q-Learning for the CartPole environment. It includes several DQN variants (standard, Double DQN, Dueling DQN, and Conv Dueling DQN), along with extensive experiments on hyperparameter tuning, ablation studies, and exploration strategies (epsilon-greedy, annealing epsilon-greedy, and softmax).

## Features

- **DQN Variants:** Standard DQN, Double DQN, Dueling DQN, and Convolutional Dueling DQN.
- **Ablation Study:** Evaluate the impact of experience replay and target networks.
- **Exploration Strategies:** Compare epsilon-greedy, annealing epsilon-greedy, and softmax policies.
- **Hyperparameter Tuning:** Automated grid search for optimal training parameters.

## Requirements

- Python 3.8
- PyTorch
- Gym (CartPole-v1)
- Other dependencies as listed in `requirements.txt`

## Setup

1. **Clone the repository:**

2. **Create and activate a virtual environment:**

3. **Install the required packages:**


## Usage

- **Run DQN agent with both Experience Replay and Target Network:**

- **Run variants (e.g., without Experience Replay or Target Network):**

- **Run DQN improvements:**

- **Hyperparameter Tuning:**

- **Ablation Study:**

- **Exploration Strategies:**


## Experiment Overview

The project evaluates different DQN configurations through:
- **Ablation Studies:** Assessing the roles of experience replay and target networks.
- **Exploration Strategy Comparison:** Analyzing learning curves using various exploration policies.
- **Model Enhancements:** Comparing standard DQN with improved variants such as Double and Dueling DQN.

## License

[MIT License]


