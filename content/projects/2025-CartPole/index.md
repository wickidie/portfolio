+++
date = '2025-01-01'
draft = false
title = 'CartPole'
tags = ['Godot', 'GameDev', 'Machine Learning'] 
+++

A game that can be played by human player or AI agent to balance the pole with moving cart.
<!--more-->

{{< youtubeLite id="FF1pyDnvCdo" label="CartPole Result demo" >}}

## Overview
This project is both a game and a simulation, where either the player can manually play or let an AI agent take control. The AI agent is trained using the AgentRL plugin, which integrates Stable-Baselines3 as the reinforcement learning framework and TensorBoard for data logging and visualization.

The game ends when the pole tilts beyond a certain angle or moves out of the arena. Balancing the pole manually is quite challenging for human players, as it requires extremely fast reaction times to counteract the pole’s rapid movements.

Below is a short clip showing the agent’s training process. In my case, training takes around 4–5 hours, depending on how long you choose to let the agent train.

{{< youtubeLite id="iI3m3sQdOyE" label="CartPole Training demo" >}}

## Tools Used
List the tools used:
- Godot
- [AgentRL Godot Plugin](https://github.com/edbeeching/godot_rl_agents)
- [Stable-baselines3](https://github.com/DLR-RM/stable-baselines3) (Reinforcement learning framework)
- [TensorBoard](https://www.tensorflow.org/tensorboard) (Tracking and visualizing tools)

## Screenshots
{{< figure src="cartpole1.png" >}}
{{< figure src="featurecartpole2.png" >}}
