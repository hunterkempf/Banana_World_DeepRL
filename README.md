[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Banana_World_DeepRL
Deep Reinforcement Learning Implementation of Collecting Banana's in the Unity Banana_Linux_NoVis/Banana.x86_64 world

### Introduction

For this project, I trained an agent to navigate (and collect bananas!) in a large, square world.  

The world looks like the gif below with the goal of collecting yellow bananas and avoiding blue bananas.

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of my agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, my agent had to get an average score of +13 over 100 consecutive episodes.

### Implementation

My Solution to the Banana World Environment uses Deep Q Learning. 

