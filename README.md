# Continuous-Control
Using deep reinforcement learning to control virtual robotic arms

![](uploads/reacher.gif)

### Introduction
 
The environment for this project involves controlling a double-jointed arm, to reach the moving target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

There are two separate versions of the Unity environment:

The first version contains a single agent.
The second version contains 20 identical agents, each with its own copy of the environment.

The second version is useful for algorithms like [PPO](https://arxiv.org/pdf/1707.06347.pdf), [A3C](https://arxiv.org/pdf/1602.01783.pdf), and [D4PG](https://openreview.net/pdf?id=SyZipzbCb) that use multiple (non-interacting, parallel) copies of the same agent to distribute the task of gathering experience. [It has been shown](https://ai.googleblog.com/2016/10/how-robots-can-acquire-new-skills-from.html) that having multiple copies of the same agent sharing experience can accelerate learning.

The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30.

### Initialization
