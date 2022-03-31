# Market Making Project

## Abstract
**Course**: MATH527: Machine Learning in Finance at the _Illinois Institute of Technology_ 

**Subject:** Create a functional Market Making environment for Reinforcement learning agents. 

**Authors:**
- Kemen GOICOECHEA: https://github.com/Kem975
- Brandon BENNITT: https://github.com/bbennitt3

**Supervisor:** Dr Matthew Dixon

## Report

This project contains a complete report at _report/MarketMaking_Report.pdf_

## Source Code

The source code is in _src/MarketMaking_Code.ipynb_. In this notebook, we create an OpenAI compliant environment for Market Making. Then, we use the Q-Learning and SARSA agents defined in the professor's notebook to make sure that they still be used.

Thereafter, we import the _stablebaselines_ library which contains Reinforcement learning agents. To use them, we change the environment to a continuous one. Then, we train _PPO2_ and _DQN_ agents on this environment. As we have studied the theory of, _On-policy_ and _Off-Policy_ agents in the course, we chose these two agents to compare the two approaches. 

To visualize and compare the two agents, we use _tensorboard_. Also, we have created numpy arrays that we update at each step to adjust the information that we want to plot.

