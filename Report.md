Navigation Project Report


Goal:

As a part of this project, we build a DQN based agent that navigates an environment with a positive one reward for collecting yellow banana and a negative one for collecting blue banana. The objective is to collect as many yellow bananas as possible


Project Summary:

1. establish state and action space using unity frameworks 
2. Take random actions and observe the reward
3. train agent by resetting the environment
4. save the model weights and reload them again to train the agent


State & Action Space summary:

The state space has 37 dimensions and Four actions are available:

`0` move forward
`1` move backward
`2` turn left
`3` turn right

DQN Algorithm

Deep Q-Learning (DQN) algorithm runs a series of tests to learn the policy that will help the agent to maximize the rewards c


Q-Function

The Q-function calculates the expected reward `R` for all possible actions `A` in all possible states `S` to achieve optimal policy


Future Plan

I plan to work on double DQN , prioritize experience replay and dueling DQN algorithms for this problem to compare the different in performance and score achieved.
