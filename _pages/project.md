---
layout: archive
title: "Projects"
permalink: /project/
author_profile: true
redirect_from:
  - /extracurricular-activities
---
## Identifying Disparities in Sepsis Treatment using Inverse Reinforcement Learning (2022)
*Authors: Hyewon Jeong, Kaiy Muhammad, Taylor Killian, Sanjat Kanjilal, Marzyeh Ghassemi*

Started as a course project for the [18.0651-Matrix Methods In Data Analysis, Signal Processing, And Machine Learning](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/) at MIT by [Prof. Gilbert Strang](https://math.mit.edu/~gs/) and ended up being my secondary project at MIT:) It has been reported in numerous studies that disparities in care for treating sepsis patients exist across the trajectory of patient stay in the emergency department and intensive care unit. Here, we apply a number of reinforcement learning techniques including behavioral cloning, imitation learning, and inverse reinforcement learning, to learn the optimal policy in the management of septic patient subgroups using expert demonstrations. Then we estimate the counterfactual optimal policies by applying the model to another subset of unseen medical populations and identify the difference in cure by comparing it to the real policy. Our data comes from the sepsis cohort of MIMIC-IV and the clinical data warehouses of the Mass General Brigham healthcare system. The ultimate objective of this work is to use the optimal learned policy function to estimate the counterfactual treatment policy and identify deviations across sub-populations of interest. We hope this approach would help us identify any disparities in care and also changes in cure in response to the publication of national sepsis treatment guidelines.