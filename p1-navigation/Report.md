# Project 1: Navigation Report

Here I describe the implementation coded for solving the Banana Navigation environment.

### Learning Algorithm
The chosen algorithm for this project is a basic Deep Q-Learning Agent (DQN).

#### Network Architecture
The neural network used for the model is made as follows:
- hidden Layer 1: 64 units with relu activation
- hidden Layer 2: 64 units with relu activation

#### Hyperparameters
| Name            | Value           | Description         |
| -------------   |:-------------   |:-----               |
| BUFFER_SIZE     | int(1e5)        | replay buffer size  |
| BATCH_SIZE      | 64              | minibatch size      |
| GAMMA           | 0.99            | discount factor     |
| LR              | 5e-4            | learning rate      |
| UPDATE_EVERY    | 4               | how often to update the network     |


### Plot of Rewards
![Navigation Rewards Plot](https://github.com/abitbetter/udacity-drl-nanodegree/blob/master/p1-navigation/image/nav_plot_rewards.png)

The environment was solved in 487 episodes.

### Ideas for Future Work
As future work and ideas it can be considered to:
- Experiment with other network sizes.
- Experiment with other hyperparameters.
- Go one step further and learn from pixels by using Convolutional Neural Networks (CNN).
