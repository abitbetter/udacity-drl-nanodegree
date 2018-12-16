# Project 1: Navigation Report

Here I describe the implementation coded for solving the Banana Navigation environment.

### Learning Algorithm *
The chosen algorithm for this project is a Deep Q-Learning Agent (DQN).

#### Pseudocode *
The implementation is based on the following pseucode from the paper [Continuous Control with Deep Reinforcement Learning](https://arxiv.org/pdf/1509.02971.pdf).

![DQN Pseudocode]()

#### Network Architectures *
The neural network used for the model is made as follows:
- 

#### Hyperparameters
| Name            | Value           | Description         |
| -------------   |:-------------   |:-----               |
| BUFFER_SIZE     | int(1e5)        | replay buffer size  |
| BATCH_SIZE      | 64              | minibatch size      |
| GAMMA           | 0.99            | discount factor     |
| LR              | 5e-4            | learning rate      |
| UPDATE_EVERY    | 4               | how often to update the network     |


### Plot of Rewards
![Navigation Rewards Plot](https://github.com/abitbetter/udacity-drl-nanodegree/blob/master/p1-navigation/image/plot_rewards.png)
The environment was solved in 487 episodes.

### Ideas for Future Work *
As future work and ideas it can be considered to:
- Experiment with other network sizes.
- Experiment with other hyperparameters.
