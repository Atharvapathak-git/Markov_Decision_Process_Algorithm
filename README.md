# Markov Decision Process (MDP) - Maze Solver 🧠🏁

This project implements a **Markov Decision Process (MDP)** agent that navigates a **5×5 maze** using **value iteration** and **policy evaluation**. The environment is a custom maze built using OpenAI Gym and Pygame, providing both logic and visualization support.

## 📌 Features

- Custom maze environment with obstacles
- MDP-based agent using value iteration
- Modular code using OpenAI Gym interface
- Visual rendering of agent navigation using Pygame
- Includes reward shaping and exploration start options

---

## 📂 Project Structure

- `Markov_Decision_Process_Algorithm.ipynb`: Jupyter Notebook implementing MDP logic and visualization
- `Maze` class (inherits from `gym.Env`)
  - Defines state space, actions, rewards, and rendering
- MDP functions:
  - `value_iteration`
  - `policy_evaluation`
  - `simulate_step`

---

## 🔧 Requirements

Install required Python libraries:

```bash
pip install gym==0.23.0 pygame matplotlib

How to Run
1. Open the notebook:
jupyter notebook Markov_Decision_Process_Algorithm.ipynb

2. Run the cells to:
Define the maze
Execute value iteration
Visualize the optimal policy path

Applications
Reinforcement Learning education
AI decision-making in grid environments
Pathfinding in robotic navigation
Game AI for maze solving

Author - Atharva Pathak
