# Navigation - Banana RL - Udacity

[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

This project aims to attempt at maximizing the score on Unity's Banana-Collector environment with Deep Reinforcement Learning. The problem was provided in the Udacity Deep Reinforcement Nanodegree [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893).

The solution presented in this notebook uses a Deep Q-Learning(DQN) to train an agent to collect bananas within the Unity's ML-environment. The agent should collect as many as possible yellow bananas (`reward = +1`) and avoid blue bananas (`reward = -1`).

The environment is sensed through a 37 dimension vector provided by the environment.
The agent has four discrete actions to choose from:
```
0 - Forward
1 - Backward
2 - Left
3 - Right
```

### Installation

The Unity ML-Agents environment only supports Python 3.6+. 

Installation instructions for the Unity ML-Agents can be found at [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) and [NumPy](http://www.numpy.org/). Note - You do not require the Unity download for this project.

The following prerequisite libraries can be installed as follows:

```
pip install numpy
pip install torch
pip install unityagents
pip install matplotlib
```


### Run
In a terminal or command window, navigate to the main directory and start the jupyter notebook with the following command:

```shell
$ jupyter notebook
```

This will open the Jupyter Notebook software and notebook in your browser which you can use to explore and reproduce the experiments that have been run. 
