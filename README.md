# Deep Reinforcement Learning Nanodegree - Project 2

This repository contains my submission for the second project of the DRL Nanodegree

## Assignment
The challenge is the solve Unity's 'Reacher'. This environment consists of 20 robot arms positioned in space with 
spheres rotating around them. The agent needs to learn to control any of the robot arms such that they follow the sphere
around them. For each time step the arm is in the sphere, the agent receives 0.1 points. The challenge is solved if the 
agent manages to collect for each robot arm on average 30 points over 100 episodes.

The agent has a 33-dimensional input at its disposal to learn from.
These 37 numbers represent the position, rotation, velocity, and angular velocities of an arm.
The agent can provide four continuous actions, ranging in value between -1 and 1, corresponding to the torques on the joints.

## Solution
The report.ipynb notebook contains and explanation of my solution.


## Replicating the solution
In order to run the files yourself, please follow these instructions:

- Create a python 3.6 environment
- Clone the repo into this environment
- Install the dependencies in the requirements.txt file in this environment
- Download the necessary Unity Environment from one of the following links and install it in the same directory as the code:
  - Linux: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
  - Mac OSX: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
  - Windows (32-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)  
  - Windows (64-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)
  

After the installation has been completed, open the Continous_Control.ipynb notebook and follow the code from there.
