Project Overview:

Defined a reinforcement learning (RL) environment based on a grid-world Markov decision process (MDP). The "GridWorldEnv" environment included states, actions, rewards, and a main objective. The environment was structured to simulate a lawn mower grid world with positive rewards (chargers) and negative rewards (stones and garbage). The goal was for the agent to reach the destination state with the maximum reward. Safety in AI was ensured by defining action and observation spaces and implementing boundaries for agent movements.

In next part applied SARSA and Q-learning algorithms to solve the defined environment. These tabular methods were used to learn and optimize the agent's policy. Hyperparameter tuning was performed to find the most efficient values for parameters such as the discount factor, epsilon, and epsilon decay rate. Results were analyzed, and reward graphs were provided for each algorithm. The performance of SARSA and Q-learning was compared, highlighting their advantages and disadvantages.

Additionally, implemented a 2-step bootstrapping SARSA and compare the results with traditional SARSA.
