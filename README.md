The repository includes the solution and report for the implementation of the Banana Game assignment for completing the Deep Reinforcement Learning Nanodegree program. In this game, the agent receives positive reward if it finds yellow bananas, and negative rewards as it finds blue bananas as it navigates through the space. The repository includes:
- a jupyter notebook which runs the game, saves the model weights and plots the total reward per episode, so we can see how many episodes are needed so that the agent achieve the desire purpose. It can be run so this procedure is done for a given range of the hyperparameters.
- 2 python files: dqn_agent.py which implements the actions of the agent for update its learning and acting, and model.py, which implements the DQN network.
The jupyter notebook loads functions in modules model.py and dqn_agent.py Before running the notebook, you should install the requirements via 
!pip install ./python
- html report to describe the solution.
- best model weights.
