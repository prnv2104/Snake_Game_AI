# AI-Based Snake Game

The classic snake game implemented using Pygame. It is integrated with the Q-learning algorithm and Deep Q-Networks (DQN) using the PyTorch framework. The goal of the game is to train the snake to make optimal decisions in each state and capture food efficiently by learning from experience.

## Features

- Q-learning Algorithm: The snake learns to select the best actions to maximize rewards using the Q-learning algorithm.
- Deep Q-Networks (DQN): DQNs can learn to estimate Q-values for a wide range of states.
- Exploration and Exploitation: The snake explores and exploits actions based on an epsilon-greedy policy.
- Reward-Based Learning: The algorithm maintains a table of Q-values that represent expected rewards for state-action pairs. It updates the Q-values using observed rewards and transitions.

## Preview
A Graph has been plotted, Score Vs No. of Games, which is compared with the mean score.


https://github.com/ashima-09/Snake_Game_AI/assets/96876403/a21cbc2a-1dc9-4797-8a29-b4f1cccedc41



## Usage

1. Clone the repository:

```bash
git clone https://github.com/ashima-09/Snake_Game_AI
```

2. Install dependencies:

```bash
pip install numpy
pip install pygame
pip install torch
pip install matplotlib
```

3. Run the game:
```bash
python main.py
```

