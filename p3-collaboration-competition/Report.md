# Project 3: Collaboration and Competition Report

Here I describe the implementation coded for solving the collaboration-competition [Unity Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment.

### Learning Algorithm
The chosen algorithm for this project is a Deep Deterministic Policy Gradient (DDPG). It is an actor-critic algorithm and uses one neural network for the actor and another for the critic.

#### Pseudocode
The implementation is based on the following pseucode from the paper [Continuous Control with Deep Reinforcement Learning](https://arxiv.org/pdf/1509.02971.pdf)

### Plot of Rewards

The environment was solved in episodes.

### Ideas for Future Work
As future work and ideas it can be considered to:
- Experiment with other network sizes.
- Experiment with other hyperparameters.
- Try other algorithms such as Proximal Asynchronous Actor-Critic Agents (A3C), Policy Optimization (PPO) and Distributed Distributional Deterministic Policy Gradients (D4PG).
- Do research on how to speed up training.
