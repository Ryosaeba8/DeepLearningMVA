# Reinforcement Learning project : Implementation of DQN 

The game :  EAT CHEESE

A rat runs on an island and tries to eat as much as possible. The island is subdivided into N*\N cells, in which there are cheese (+0.5) and poisonous cells (-1). The rat has a visibility of 2 cells (thus it can see 25 cells). The rat is given a time T to accumulate as much food as possible. It can perform 4 actions: going up, down, left, right.

The goal is to code an agent to solve this task that will learn by trial and error
We've implemented various models and configurations
### A fully connected model with 3 layers
 <img src="https://github.com/Ryosaeba8/DeepLearningMVA/blob/master/rl_project/videos/fc.gif" width="400"/>  
### A CNN network
 <img src="https://github.com/Ryosaeba8/DeepLearningMVA/blob/master/rl_project/videos/cnn.gif" width="400"/>  
### CNN with an adaptive exploration rate
 <img src="https://github.com/Ryosaeba8/DeepLearningMVA/blob/master/rl_project/videos/explore.gif" width="400"/>  
### A Mimic model
 <img src="https://github.com/Ryosaeba8/DeepLearningMVA/blob/master/rl_project/videos/mimic.gif" width="400"/>  
