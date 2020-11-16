# rl_banana_x86_64
Reinforcement Learning Project using Banana Collection Unity Environment

# Project Description
The agent is trained to navigate a 3D environment and collect bananas. When a yellow banana is collected, reward of +1 is given; when a blue banana is collected, reward of -1 is given. The goal of the agent is to collect yellow bananas while avoiding blue bananas.

The state space consists of 37 dimensions that include ray-based perception of objects around the agent's forward direction and the agent's velocity. There are 4 discrete actions available for the agent: move forward, move backward, turn left, and turn right.

The environment is episodic, and it is considered solved when an average score of +13 over 100 episodes is achieved.

# Getting Started
To install all the necessary dependencies for this project, run: !pip -q install ./python

# Run the Code
To run the code for training the agent, open the jupyter notebook named learning.ipynb and run all cells. The training automatically terminates when the reward requirement is reached for the agent. It will save the model output as checkpoint.pth.
