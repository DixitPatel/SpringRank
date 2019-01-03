# SpringRank
SprinRank is a physically-inspired ranking algorithm to infer hierarchical rankings of nodes in a directed network. More details are in the paper [here](https://arxiv.org/abs/1709.09002).
Here I use SpringRank to find layer interdependence in a multi-layered network
There are three jupyter notebooks provided where we test SpringRank on three different types of directed networks :
1. Synthetic Network
2. Tennis (2008 - 2018)
3. Professional Hockey Games (NHL)

Plots are provided at the bottom in each notebook to understand SpringRank's performance against these datasets. Below is one example.

1. Tennis (2008 - 2018)
(https://github.com/DixitPatel/SpringRank/tree/master/data/tennis.png)

This plot shows the effect of using SpringRank to predict player performances in future years. In particular, we train a model for the year 2008 and use it to predict match outcomes for the years 2009 through 2018.
There two things we observe here :
1. SpringRank does better than randomly guessing match outcomes  (blue vs black dotted lines)
2. The ability to predict performance of players further down the years, gradually decreases and essentially behaves like a random model after a few years.

