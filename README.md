# Overview: Reinforcement Learning in Grid World Environment

This repository contains an implementation and analysis of reinforcement learning algorithms in a grid world environment. The goal of this project is to provide insights into how SARSA and Q-learning algorithms perform in a defined environment and to optimize hyperparameters for efficient learning.

## Environment Description

The environment, referred to as 'GridWorldEnv,' is a 5x5 grid world with the following characteristics:
- Starting point, goal point, and various rewards (chargers, mega chargers) and obstacles (stones, garbage).
- Agent can move in four directions: up, down, right, left.
- States represent the agent's location in the grid world, and actions represent movement directions.
- The objective is to reach the goal state while avoiding obstacles, with specific rewards and penalties.

## Tabular Methods

Implemented three tabular methods for reinforcement learning: SARSA, Q-learning, and N-step SARSA. Here's a brief overview of each:
- SARSA: On-policy algorithm, estimating the optimal policy and action-value function.
- Q-learning: Off-policy algorithm, estimating the optimal action-value function.
- N-step SARSA: Extension of SARSA, updating multiple state-action pairs.

## Results

Evaluated the performance of SARSA and Q-learning in the environment and present key findings:
- SARSA: Lower epsilon values lead to higher rewards.
- Q-learning: Total rewards per episode increase over time.

## Comparison of Algorithms

Comparing SARSA and Q-learning:
- Q-learning reaches higher initial rewards but is less stable.
- SARSA is more stable and suitable for maximizing cumulative rewards.

## Hyperparameter Tuning

Conducted hyperparameter tuning for both algorithms. Here are the findings:
- SARSA: Higher discount factors improve reward collection.
- SARSA: Epsilon values didn't show significant changes.
- SARSA: Smaller epsilon decay rates are better for learning.
- Q-learning: Similar trends in hyperparameter tuning as SARSA.

## Suggested Hyperparameters

Based on the analysis, the following hyperparameters are suggested for efficient learning:
- SARSA: Use a higher discount factor.
- SARSA: Epsilon values can be kept consistent.
- SARSA: Use a smaller epsilon decay rate.
- Q-learning: Similar suggestions as SARSA.

Feel free to explore the code and experiment with different hyperparameters in your own grid world environments.

For more details, refer to the full report in the 'Report' directory.

