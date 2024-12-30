# Maze Solver with Reinforcement Learning (RL) using Reward Shaping in Unity

This project demonstrates a **Maze Solver** game built with **Reinforcement Learning (RL)** using **Reward Shaping** techniques, developed as part of Advanced Topics on Intelligent Systems for FEUP university. The goal of this project is to solve a maze by training an AI agent using RL, improving its decision-making process through reward shaping to navigate efficiently.

### Key Features:
- **Reinforcement Learning**: The AI agent learns optimal movement strategies through trial and error.
- **Reward Shaping**: A technique used to modify the reward function to speed up learning by guiding the agent towards desirable behaviors.
- **Unity Game Engine**: Developed using Unity, providing a flexible environment for visualizing and interacting with the maze and the RL agent.
- **Cross-Platform**: The project includes executable files for **Linux**, **Mac**, and **Windows** systems, ensuring compatibility across different platforms.

### Installation & Usage:
1. **Download the Executable**:
   - You can find the pre-built executables for **Linux**, **Mac**, and **Windows** in the `Releases` section of this repository.

2. **Run the Game**:
   - Simply download the appropriate file for your operating system and run the executable.

3. **Game Instructions**:
   - The game starts with a main menu that leads to 3 different Scenes.
   - The agent must find the shortest path from the start to the end using reinforcement learning techniques.
   - The agent receives positive or negative rewards based on its actions (moving in the right direction or hitting a wall).
   - You can observe the agent's learning progress and decision-making process over time.

### How It Works:
- **Reinforcement Learning**:
  - The RL model is trained using an **epsilon-greedy** policy for exploration and exploitation.
  - The agent learns by receiving **rewards** for correct actions (e.g., moving toward the goal) and **penalties** for incorrect actions (e.g., hitting a wall).
  - The training process involves updating the agent's policy using algorithms like **Q-learning** or **Deep Q-Networks (DQN)**.

- **Reward Shaping**:
  - Reward shaping is employed to accelerate learning by modifying the reward function.
  - The agent is incentivized to choose better paths by adding intermediate rewards for partial successes, such as getting closer to the goal or avoiding obstacles.

### Technologies Used:
- **Unity**: Game engine for creating and visualizing the maze environment and the RL agent.
- **Reinforcement Learning (RL)**: The core technique for training the agent, allowing it to improve its decision-making over time.
- **Reward Shaping**: Used to modify the reward function, providing additional guidance to the agent during training.

### Challenges:
- **Maze Generation**: The maze is procedurally generated, which makes training more challenging by varying the environment for each episode.
- **Exploration vs Exploitation**: Balancing exploration (trying new actions) and exploitation (relying on known actions) during training was crucial to improve the agent's performance.
- **Reward Shaping**: Designing an effective reward shaping function that accelerates learning without compromising the agent's ability to generalize to new mazes was a key challenge.

### Conclusion:
This project showcases how **Reinforcement Learning** and **Reward Shaping** can be applied to solve dynamic and complex maze navigation problems. The game provides an interactive way to visualize RL concepts while offering a challenging environment the AI agent.
