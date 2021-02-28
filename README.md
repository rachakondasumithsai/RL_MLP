# RL_MLP
Implementation of model free Reinforcement Learning Network with MNIST data.

Implemented three models.
Used MNIST dataset.
Here models are implemented like DQN model.

It is a combination of predicting one hot representation of a given MNIST sample and then using this as the starting state of an agent in a maze.
The first part is a pre trained MLP for MNIST and second is RL model that predicts the next state or count either up or down for a given image.

Model-1 has freezed layers (first part pre trained layers).

Model-2 has all unfreazed leayers with pre trained network.

Model-3 has all layers unfreazed but no pretrained network.
