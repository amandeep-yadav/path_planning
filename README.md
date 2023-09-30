# path_planning
This repository contains the implementation of Q-learning and Deep Q-learning algorithms for finding the shortest path between two points in various environments. The project also utilizes Bellman's equation for Q-value computation and trains the agent using the epsilon-greedy method to balance exploration and exploitation during training. The trained agent's efficiency in navigation and obstacle avoidance in complex situations has been successfully tested.  

## Table of Content
Inroduction  
Installation  
Usage  
Algorithm  
Results  
Contribution   
Licence  
## Introduction  
Pathfinding is a fundamental problem in robotics and artificial intelligence. This project focuses on using reinforcement learning techniques to find the shortest path between two points in different environments. Specifically, we implement Q-learning and Deep Q-learning algorithms, which are widely used in reinforcement learning for tasks like this.  
### Features  
#### Q- learning and Deep Q-learning
 Both traditional Q-learning and its deep learning variant, Deep Q-learning, have been implemented for pathfinding.  
 #### Bellman's Equation:  
 We utilize Bellman's equation to calculate Q-values, which is a key component in reinforcement learning.  
 #### Epsilon- Greedy Strategy  
 During training, we employ the epsilon-greedy method to strike a balance between exploration and exploitation.  
 
 #### Environment Testing 
 The trained agent has been rigorously tested in various environments to assess its efficiency in navigating and avoiding obstacles, especially in complex.  
 ## Installation
 clone the repository  
(https://github.com/amandeep-yadav/path_planning.git)  
 1. Run the main_pathplanning file  
## Algorithms
### Q-learning
Q-learning is a model-free, reinforcement learning algorithm that seeks to find the optimal action-selection policy for a given finite Markov decision process (MDP). It iteratively updates the Q-values of state-action pairs based on the Bellman equation:  
Q(s, a) = Q(s, a) + α [R(s) + γ * max(Q(s', a')) - Q(s, a)]     

Where:  

Q(s, a) is the Q-value for state s and action a.  
α is the learning rate.  
R(s) is the immediate reward upon transitioning to state s.   
γ is the discount factor.   
max(Q(s', a')) represents the maximum Q-value for the next state s' and all possible actions a'    
### Deep Q- learning
Deep Q-learning extends Q-learning by using deep neural networks to approximate the Q-values. This allows the algorithm to handle high-dimensional state spaces, making it suitable for more complex tasks.
## Results
The trained agent's performance and efficiency in finding the shortest path and avoiding obstacles in various environments are demonstrated in the output image.
