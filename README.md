[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation
## Payam Mousavi

### Introduction

For this project, I trained an agent to navigate (and collect bananas!) in a large, square world. A [DQN agent](https://deepmind.com/research/dqn/) was implemented to achieve the this goal.

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of the agent was to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent was required to get an average score of +13 over 100 consecutive episodes.



### Instructions

First, install all required packages:

`pip install -r requirements.txt`

All further instructions and experiments can be found in **`Project_1_Bananad_Navigation.ipynb`**
