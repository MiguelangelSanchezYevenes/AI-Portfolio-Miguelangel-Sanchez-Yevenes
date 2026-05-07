
## Problem Statement

The goal of this lab was to teach an AI agent how to balance a pole on a moving cart using reinforcement learning. The challenge was for the agent to keep the pole upright for as long as possible without falling over. The lab focused on showing how an agent can improve its behavior through trial and error using Q-learning.

## Approach and methodology

The lab used the CartPole environment from the Gymnasium library in Python. A random agent was tested to show what happens when an AI has no training. It selected actions without any strategies, then it was recorded. Next, a Q-learning agent was implemented. The agent learned by interacting with the environment repeatedly over many episodes. It received rewards for keeping the pole balanced and updated its Q-table. Graphs were also created using Matplotlib to visualize the agent’s improvement over time.

## Results and evaluation

The random agent performed poorly because it had no learning ability and could only keep the pole balanced for a short time but after training, the Q-learning agent showed major improvement. This made it better to balance the pole for longer periods of time. The results demonstrated that reinforcement learning allows an AI agent to learn from experience and improve its decisions over time.

## Your learning outcomes

I learned: 

The basics of reinforcement learning

Learned how Q-learning works

How agents update Q-values and balance exploration versus exploitation.
