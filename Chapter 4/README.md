HomeWork 4
Wumpus World is a classic problem in artificial intelligence and reinforcement learning that involves a grid-based environment where an agent must navigate to find gold while avoiding hazards such as pits and Wumpus.

Grid Navigation Objectives: The agent must learn to navigate the grid efficiently.

Avoid Hazards: The agent must learn to avoid potholes and Wumpus.

Collect gold: The agent must find and collect gold.

Kill Wumpus: The agent can shoot an arrow to kill the Wumpus and eliminate it as a threat.

Set up the grid environment: a 4x4 grid where each cell can be empty, contain a pit, Wumpus or gold.

Action space: move up, down, left, right.

Shoot an arrow in any of the four directions (up, down, left, right) (score).

Visualizations: Wumpus moves left, right, up, or down on the grid with each action change (points).

Reward space:

100+ to get gold
-1000 for falling into a pit or being eaten by Wumpus
50+ points for killing Wumpus
-1 for each move
Environment Definition: Create a 4x4 grid with desired positions for pits, wumpus and gold. Define the initial state and the possible states after each action.

Setting parameters:

Learning rate: 0.1
Discount factor: 0.9
Discovery rate: starts from 1.0 and decreases over time According to the general things said about the problem.

Q-Learning Method
Deep Q-Learning (DQN) Method
Policy Performance
Learning Efficiency
