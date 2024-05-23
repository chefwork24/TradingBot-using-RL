
# RL based Trading Bot




## Overview

This project contains the implementation of a Stock Trading Bot using Deep Reinforcement Learning.Implementation of the different RL algorithms such as A2C(Actor Critic), PPO(Proximal Policy Optimisation), DQN(Deep Q Network) are done using stable_baselines3 models.



## Results

The comparison between different RL algorithms is done using the net profit as a metric.

A2C:

Total_profit:0.33830961836684514

Total_rewards:-26.637596130371094

DQN:

Total_profit: 0.20573314333459072

Total_rewards:-28.715072631835938

PPO:

Total_profit: 0.07167917680459142

Total_rewards:105.96749496459961


Hence we can see that A2C perform 64% better than DQN which perform 187% better than PPO



## Improvements

1) Since the stock market is a very dynamic system ,algorithms like SAC can perform better but it requires continous actions ,so custom environment can be made to be compatible with continousactions.

2) Ensemble methods could imporve the peformance.

3) Testing with different stock prices can give more idea about the general performance of the algorithms


## Data
The NVIDIA stock prices been used for training and testing.
 - [Source:NVIDIA Dataset]( https://www.kaggle.com/datasets/prajwaldongre/nvidia-corp-share-price-2000-2024 )
