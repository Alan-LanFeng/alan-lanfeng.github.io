---
title: Benchmarking Safety Performance in Reinforcement Learning
date: 2023-10-26
links:
  - type: site
    url: project/scikit/FRL_report.pdf
tags:
  - Reinforcement Learning
  - Safety
---

In reinforcement learning (RL) tasks, the agents have to explore their environments to find an optimal policy that maximizes the long-term discounted return based on a designated value function. However, in some real-world situations where the safety of the agent is particularly crucial, (e.g. expensive robot arms; implementation of RL in autonomous driving), safe exploration becomes paramount during the training and testing processes in the real world. In this work, we make three noteworthy contributions to advance the study of safe exploration. First, we introduce two sets of metrics to evaluate safe RL algorithms’ performance in the training and testing phases, respectively, which complementarily enhance each other and reveal some details that cannot be caught by either phase individually. Second, in the testing phase, the vast majority of the published results of safe RL benchmarks are usually expressed in terms of point estimates of aggregate performances such as mean and median scores across different tasks, which ignores the statistical uncertainty raised by the limited number of training runs. Given the current status quo, we are the first to include statistical uncertainty in the safe RL algorithm’s testing-phase evaluation to avoid discrepancies between the point estimates and the true distributions of data. Last but not least, to enhance the diversity of the evaluated algorithms, we extend our benchmark from model-free to model-based safe RL algorithms, and make some improvements on the algorithms for comparison.
<!--more-->
