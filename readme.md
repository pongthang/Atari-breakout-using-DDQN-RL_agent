# Atari Breakout RL Agent

This project is a demonstration of training a Reinforcement Learning (RL) agent to play the classic Atari Breakout game using Double Deep Q-Networks (DDQN). 

## Project Overview

The goal of this project is to develop an RL agent that can learn to play Atari Breakout effectively. The core components of this project include:

1. **Input Data**: The RL agent receives input in the form of four consecutive images, representing subsequence time-steps of the Breakout game. These images are essential for the agent to understand the dynamics of the game, particularly the behavior of the ball.

2. **Q-Function**: To make decisions about its actions, the RL agent utilizes a Q-function. In this project, a Convolutional Neural Network (CNN) is employed to extract important features from the input images. After passing through the CNN, the extracted features are further processed by a fully connected neural network to estimate the Q-values for various actions.

3. **RL Agent Training**: With the Q-function in place, the RL agent is trained to play the game effectively. It learns to make decisions that maximize its expected cumulative rewards over time. Through repeated interactions with the game environment, the agent improves its decision-making abilities and learns optimal strategies.

## Why Four Images?

Using four consecutive images as input provides the RL agent with a richer understanding of the game dynamics. By considering more frames, the agent can better infer the position, velocity, and acceleration of the ball, which are critical for making accurate decisions. While it is possible to use three images, the additional frame enhances the agent's ability to anticipate and react to changes in the game state.

## Dependencies

Before running this project, ensure you have the following dependencies installed:

- Python 3.x
- PyTorch 
- Gym (OpenAI Gym, a toolkit for developing and comparing RL algorithms)
- opencv
- numpy
- matplotlib

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine

2. Install the required dependencies as specified above

3. Run the jupyter notebook to train the RL agent:


4. Monitor the training progress, and once the agent is adequately trained, you can test its performance in the game.

## Configuration

Adjust hyperparameters, network architecture, and other settings to fine-tune the agent's performance.

## Result

https://github.com/pongthang/Atari-breakout-using-DDQN-RL_agent/assets/57061570/62cfea31-e780-4345-b99b-e42fac297234


Enjoy training your RL agent and watching it master Atari Breakout! 🎮🕹️
