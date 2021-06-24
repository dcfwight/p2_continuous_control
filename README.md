# p2_continuous_control
This is the DDPG project 2 for Udacity Reinforcement Learning Nano-degree.

## Description of environment
The environment is a [Unity]('https://github.com/Unity-Technologies/ml-agents/blob/main/docs/Learning-Environment-Examples.md#reacher') environment called "Reacher"
In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

## "Solution"
To solve the environment, the agent must achieve an average score of > 30 over 100 consecutive episodes

## Framework used
I plan on using an Actor-critic DDPG model ("Deep Deterministic Policy Gradient")

## Starting point
I started off using the [DDPG pendulum]('https://github.com/udacity/deep-reinforcement-learning/tree/master/ddpg-pendulum') code from Udacity as a starting point

## Results
You can see the results in two ways:
1. Run the Jupyter notebook - 'Continous_control_2.ipynb'
1. Read through the PDF of the completed Jupyter notebook - 'Continuous_control_2.pdf'

After many iterations through different hyperparameters, I completed the task.
Chart of moving average over 100 episodes is shown here:
![Training results](/solved.jpg "Training results")

# Notes on 

