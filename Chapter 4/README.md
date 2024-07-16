# MachineLearning2024 - HomeWork 4
Welcome to the official GitHub repository for the "Machine Learning" course for the Spring 1403 at **Khaje Nasir Toosi University of Technology (KNTU)**. This project explores advanced topics in machine learning, focusing on reinforcement learning algorithms such as Q-learning and Deep Q-Network (DQN).
## Introduction
This repository includes the code, datasets, and reports for the fourth mini project. The project involves implementing and comparing reinforcement learning algorithms in a simulated environment, specifically the Wumpus World. Detailed instructions and requirements for each part are provided below.

Wumpus World is a classic problem in artificial intelligence and reinforcement learning that involves a grid-based environment where an agent must navigate to find gold while avoiding hazards such as pits and Wumpus.

*Grid Navigation Objectives:* The agent must learn to navigate the grid efficiently.

*Avoid Hazards:* The agent must learn to avoid potholes and Wumpus.

*Collect gold:* The agent must find and collect gold.

*Kill Wumpus:* The agent can shoot an arrow to kill the Wumpus and eliminate it as a threat.

*Set up the grid environment:* a 4x4 grid where each cell can be empty, contain a pit, Wumpus or gold.

*Action space:* move up, down, left, right.

*Shoot an arrow in any of the four directions (up, down, left, right) (score).*

*Visualizations:* Wumpus moves left, right, up, or down on the grid with each action change (points).

**Reward space:**

1. 100+ to get gold
2. -1000 for falling into a pit or being eaten by Wumpus
3. 50+ points for killing Wumpus
4. -1 for each move
*Environment Definition:* Create a 4x4 grid with desired positions for pits, wumpus and gold. Define the initial state and the possible states after each action.

**Setting parameters:**

1. Learning rate: 0.1
2. Discount factor: 0.9
3. Discovery rate: starts from 1.0 and decreases over time According to the general things said about the problem.

### Important Dates
- **Project 4 Submission Deadline:** 18:00, Monday, July 11, 140

### Project Requirements
1. Report: A comprehensive textual report is required, covering all aspects of the project. This includes explanations and results for each section.
2. Code Submission: All code must be uploaded to both the university portal and GitHub.
3. Structured Presentation: The report should follow a structured format, with clear explanations for each question and section.
4. Google Colab Integration: Ensure your Colab notebooks are set to Public access and include all necessary outputs and code cells.

**Links:**
      - [Google Drive](https://drive.google.com/drive/folders/147v_LVsJreU_Pg6KVc4gar_UjFSXKEP7)

## Project Tasks
- Q-Learning Method
- Deep Q-Learning (DQN) Method
- Policy Performance
- Learning Efficiency
### Task 1: Q-learning Implementation in Wumpus World
1. **Environment Setup:** Initialize the Wumpus World environment using a 4x4 grid with a fixed window size. Define the observation space and action space, including movements and shooting actions.
2. **Algorithm Implementation:** Implement the Q-learning algorithm. Define the Q-table, reward structure, and learning parameters. Ensure the agent can learn to navigate the environment and avoid hazards.
3. **Training and Evaluation:** Train the agent using Q-learning and evaluate its performance. Adjust the parameters as needed to improve learning efficiency and success rate.
### Task 2: Deep Q-Network (DQN) Implementation
1. **Network Architecture:** Define the architecture for the Deep Q-Network (DQN), including input layers, hidden layers, and output layers. Use appropriate activation functions and optimizers.
2. **Replay Buffer:** Implement a replay buffer to store experiences and use them for training to break the correlation between consecutive experiences.
3. **Training Process:** Train the DQN agent using the experiences stored in the replay buffer. Periodically update the target network to stabilize training.
4. **Evaluation:** Evaluate the performance of the DQN agent and compare it with the Q-learning agent. Use metrics such as cumulative reward and success rate to assess performance.
### Task 3: Enhanced Reward Structure and Additional Scenarios
1. **Modified Reward Structure:** Experiment with different reward structures to encourage the agent to find gold and avoid dangers more effectively. Compare the performance of agents with different reward settings.

## Contribution Guidelines
1. **Fork the Repository:** Make a copy of this repository on your GitHub account.
2. **Clone the Repository:** Download your copy to your local machine.
3. **Create a New Branch:** Work on a separate branch for your changes.
4. **Commit and Push:** Save your changes and push them to your GitHub.
5. **Pull Request:** Submit a pull request to merge your changes into the main repository.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- [Google Colab](https://colab.research.google.com/)
- [TensorFlow Documentation](https://www.tensorflow.org/)

***
This README provides a comprehensive guide for anyone looking to understand, contribute to, or use the course projects. Ensure all links and information are up to date before finalizing the document.
