# Reinforcement-Learning
The environment ‘GridWorldEnv’ defined is a 5x5 grid world with a starting point, a goal point,
and several negative rewards such as stones, garbage, and positive reward such as charger and
mega charger. The agent can move in four directions: up, down, right, and left. The states represent
the location of the agent in the grid world, and the actions represent the direction the agent can
move. Once the agent hits a state with a reward (i.e., charger, mega charger, stone, or garbage), the
reward will disappear. The main objective of the agent is to reach the goal state while avoiding
obstacles, and it receives a positive reward of 10 when it reaches the goal state and reward of +5
and +6 while passing the charger and mega charger, and negative rewards for different types of
obstacles.
Theme: ‘GridWorldEnv’ is a lawn mower grid of 5*5. With negative rewards for stones and
garbage and positive reward for chargers.
Actions: {‘Up’, ‘Down’, ‘Right’, ‘Left’}
States: {S1 = (0,0), S2 = (0,1), S3 = (0,2), S4 = (0,3), S5 = (0,4), S6 = (1,0), S7 = (1,1), S8 = (1,2),
S9 = (1,3), S10 = (1,4), S11 = (2,0), S12 = (2,1), S13 = (2,2), S14 = (2,3), S15 = (2,4), S16 = (3,0),
S17 = (3,1), S18 = (3,2), S19 = (3,3), S20 = (3,4), S21 = (4,0), S22 = (4,1), S23 = (4,2), S24 =
(4,3), S25 = (4,4)}
Rewards:
1. +10 for reaching the goal state.
2. -6 for hitting the stone.
3. -5 for hitting the garbage.
4. +5 for hitting the charger.
5. +6 for hitting the mega charger.
6. -3 for hitting the small stone.
7. 0 for any other move.
The rewards will disappear after the lawn mower hits a state with reward for the first time.
Objective: The agent needs to reach the goal state while avoiding obstacles.
Other parameters:
1. The start state is (0, 0).
2. The goal state is (4, 4).
3. The stone location is (3, 0).
4. The small charger location is (1, 0).
5. The garbage location is (0, 2).
6. The mega charger location is (3, 2).
7. The large charger location is (1, 3).
The environment is rendered using the render function, which shows the grid world with the
obstacles, agent, and goal state.
