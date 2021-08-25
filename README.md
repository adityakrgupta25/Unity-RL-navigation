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

The environment will be considered solved when we are able to achieve an average score of `+15` over 100 episodes.

### Installation

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.
2. The following prerequisite libraries can be installed as follows:

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
