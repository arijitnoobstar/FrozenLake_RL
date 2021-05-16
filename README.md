# FrozenLake_RL

This project provides the code for a Reinforcement Learning agent to learn to navigate any N by M gridworld. The gridworld consists empty slot where an agent can go to, and holes which terminate the path of the agent. The aim is to reach the goal without falling into any holes. Any attempt to leave the gridworld border will force the agent to stay in the same spot. The state transition function for all states is deterministic and follows the agent's intended movement (i.e. if the agent wishes to move left, it will move left with 100% probability). The image below shows an example of a 4 by 4 gridworld.

<img src="https://github.com/arijitnoobstar/FrozenLake_RL/blob/main/gridworld.png" width="200" />

The following tabular reinforcement learning algorithms are supported for this gridworld:

 1. Q Learning
 2. SARSA
 3. First-Visit Monte-Carlo with Exploring Starts
 4. Every-Visit Monte-Carlo with Exploring Starts
 5. First-Visit Monte-Carlo without Exploring Starts
 6. Every-Visit Monte-Carlo without Exploring Starts

The image below shows an example of a policy learnt via Q-Learning for the 4 by 4 gridworld

<img src="https://github.com/arijitnoobstar/FrozenLake_RL/blob/main/4by4policy.png" width="200" />

The following features are also supported for a custom N by M gridworld:

 1. Generate a gridworld of specified N and M
 2. Choose the probability of a grid cell being a hole (randomly generated)
 3. Choose the starting locations of agent and goal
 4. Depth-First search to ensure random gridworld has a valid path from agent to goal
 5. Custom epsilon schedule to manage the balance between exploration & exploitation

The images below show the examples of a custom 10 by 10 gridworld & policy,

<p float="left">
    <img src="https://github.com/arijitnoobstar/FrozenLake_RL/blob/main/gridworld_large.png" width="300" hspace="40"/>
    <img src="https://github.com/arijitnoobstar/FrozenLake_RL/blob/main/10by10policy.png" width="300" >
</p>

The following post-processing plots can also be derived

<p float="left">
    <img src="https://github.com/arijitnoobstar/FrozenLake_RL/blob/main/QinitConvergence.png" width="200" hspace="10"/>
    <img src="https://github.com/arijitnoobstar/FrozenLake_RL/blob/main/QmovingaverageConvergence.png" width="200" hspace="10"/>
    <img src="https://github.com/arijitnoobstar/FrozenLake_RL/blob/main/percentagegoalreached.png" width="200" >
</p>


All instructions for using the code can be found in the [.IPYNB file](https://github.com/arijitnoobstar/FrozenLake_RL/blob/main/FrozenLake_RL.ipynb) in this repository

## Collaborators

[Arijit Dasgupta](https://github.com/arijitnoobstar)
