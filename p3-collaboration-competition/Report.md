# Project 3: Collaboration and Competition Report

Here I describe the implementation coded for solving the collaboration-competition [Unity Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment.

### Learning Algorithm
The chosen algorithm for this project is a Deep Deterministic Policy Gradient (DDPG). It is an actor-critic algorithm and uses one neural network for the actor and another for the critic.

#### Pseudocode
The implementation is based on the following pseucode from the paper [Continuous Control with Deep Reinforcement Learning](https://arxiv.org/pdf/1509.02971.pdf).

![DDPG Pseudocode](https://github.com/abitbetter/udacity-drl-nanodegree/blob/master/p3-collaboration-competition/image/ddpg%20pseudocode.png)

#### Network Architectures
For the Actor:
- text

For the Critic:
- text

#### Hyperparameters
| Name            | Value           | Description         |
| -------------   |:-------------   |:-----               |
| BUFFER_SIZE     | int(1e5)        | replay buffer size  |
| BATCH_SIZE      | 256             | minibatch size      |
| GAMMA           | 0.99            | discount factor     |
| TAU             | 1e-3            | for soft update of target parameters     |
| LR_ACTOR        | 1e-4            | learning rate of the actor     |
| LR_CRITIC       | 1e-3            | learning rate of the critic     |
| WEIGHT_DECAY    | 0               | L2 weight decay     |
| EPSILON_MAX     | 1.              | epsilon max value     |
| EPSILON_MAX     | 0.05            | epsilon min value     |
| EPSILON_DECAY   | .99995          | epsilon decay factor     |


### Plot of Rewards

The environment was solved in episodes.

### Ideas for Future Work
As future work and ideas it can be considered to:
- Experiment with other network sizes.
- Experiment with other hyperparameters.
- Try other algorithms such as Proximal Asynchronous Actor-Critic Agents (A3C), Policy Optimization (PPO) and Distributed Distributional Deterministic Policy Gradients (D4PG).
- Do research on how to speed up training.
