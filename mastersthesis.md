---
layout: page
title: Predicting Agent Behavior by Estimating Motion Planners
---

### Predicting Agent Behavior by Estimating Motion Planners

![RRT* LSTM MDN on curved path](/assets/img/mastersresults.png)

Autonomous vehicles typically use a path planner to plot a trajectory for themselves. If we assume that other vehicles are also using a path planner, we can use that assumption to predict where they're headed.

For this study, I used a sample-based planner, Rapidly-exploring Random Tree (RRT), and a trained distribution that was a combination of two networks: a Long Short-Term Memory (LSTM) network and a Mixture Density Network (MDN). These networks were trained on a dataset of observed vehicle trajectories. This approach allowed me to assume that other vehicles had their own internal planner, but that planner was weighted by vehicle trajectories that we've seen in the past.

After comparing this new method to several baselines, I showed that methods that used a path planner as part of the vehicle trajectory prediction perform better than methods that don't use a path planner. However, the new method did not outperform all of the baselines, indicating that more study is needed.

[Here's the link to the full text.](https://scholarwolf.unr.edu/server/api/core/bitstreams/348556f1-b6a8-48cb-8b72-99753a707c6d/content)
