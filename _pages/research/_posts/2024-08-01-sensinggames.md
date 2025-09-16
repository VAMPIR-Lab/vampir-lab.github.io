---
layout: project
category: past-projects
title: Online Competitive Information Gathering for Partially Observable Trajectory Games
authors: Mel Krusniak, Hang Xu, Parker Palermo, and Forrest Laine
arxiv: https://arxiv.org/abs/2506.01927
image: sensing_games.png
venue: RSS 2025
permalink: 'projects/sensing_games'
date: 2024-08-01
abstract: "Game-theoretic agents must make plans that optimally gather information about their opponents. These problems are modeled by partially observable stochastic games (POSGs), but planning in fully continuous POSGs is intractable without heavy offline computation or assumptions on the order of belief maintained by each player. We formulate a finite history/horizon refinement of POSGs which admits competitive information gathering behavior in trajectory space, and through a series of approximations, we present an online method for computing rational trajectory plans in these games which leverages particle-based estimations of the joint state space and performs stochastic gradient play. We also provide the necessary adjustments required to deploy this method on individual agents. The method is tested in continuous pursuit-evasion and warehouse-pickup scenarios (alongside extensions to N>2 players and to more complex environments with visual and physical obstacles), demonstrating evidence of active information gathering and outperforming passive competitors. "
---

We became interested in partially observable (imperfect information) game theoretic
interactions in continuous spaces, like those typically encountered in robotics. This work
explores a simple horizon-based approach to seeking good performance in such games. 