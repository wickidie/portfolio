+++
date = '2025-01-01'
draft = false
title = 'CliffWalking'
tags = ['Godot', 'GameDev', 'Machine Learning'] 
+++

A game where you must move the player to the finish, playable by either a human player or an AI agent.
<!--more-->

{{< youtubeLite id="GTt1V9S04GA" label="CliffWalking Result demo" >}}


## Overview
This is a game where you must move the player to the yellow finish tile while avoiding cliffs and finding the shortest path. The level is surrounded by dark blue walls, which the player cannot pass through. Green tiles serve as safe spaces, while red tiles represent cliffs stepping on one will teleport the player back to the white starting tile.

Although the game itself is easy to solve, it serves as an excellent environment for testing and experimenting with reinforcement learning techniques.

Below is a short clip showing the agent’s training process. In my case, training takes around 10-20 minutes, depending on how long you choose to let the agent train.

{{< youtubeLite id="jPUCwKP_6xs" label="CliffWalking Training demo" >}}

## Tools and Frameworks Used
List the tools and frameworks:
- Godot
- [AgentRL Godot Plugin](https://github.com/edbeeching/godot_rl_agents) (Godot Plugin for )
- [Stable-baselines3](https://github.com/DLR-RM/stable-baselines3) (Reinforcement learning framework)
- [TensorBoard](https://www.tensorflow.org/tensorboard) (Tracking and visualizing tools)

## Screenshots
{{< figure src="featurecliffwalking2.png" >}}
{{< figure src="cliffwalking1.png" >}}