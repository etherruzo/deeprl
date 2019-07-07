# Project Details

The project aims to solve the Banana Game problem within the scope of the first assignment to complete Udacity’s Nanodegree Program on Deep Reinforcement Learning.
The agent navigates a square world and tries to collect as many yellow bananas as it can, avoiding blue bananas. Therefore, a reward of +1 is provided for collecting a yellow banana, while a reward of -1 is provided for collecting a blue banana.
The state space has 37 dimensions and includes information about the agent's velocity and position of objects around the agent's forward direction.
The action space has 4 dimensions: the agent can move forward, backward, turn left and turn right.
The game is considered to be solved when the average reward over 100 episodes is larger than 13. 

# Getting Started

The project has several dependencies that are included in the file requirements.txt in the python folder of the repository. To install them, we can run from the jupyter notebook:
```
!pip install ./python
```
# Instructions

The notebook can be run in three ways.

### Training the agent and saving the results

For training the agent to know how to play the game, you should run the notebook up until the end of section 2a. This will carry out the experiments for several value of the parameters.
This will generate a dictionary containing the increase in rewards as the number of episodes is increase, and save the corresponding weights as model checkpoints.

### Loading the results to see the performance

For this purpose you only need to run section 2b, and a dictionary with the dependence of the rewards on the episode will be loaded and visualized for different values of the parameters.

### Loading best model to see the agent play in your local computer

For this purpose you only need to run section 3 of the notebook, which will load the best model weights; you can then set the local path where you want to store them in order to visualize the performance in your local computer.