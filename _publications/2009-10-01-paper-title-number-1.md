---
title: "A deep learning framework for modelling left-turning vehicle behaviour considering diagonal-crossing motorcycle conflicts at mixed-flow intersections"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: # 'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-11-01
venue: 'Transportation research part C: emerging technologies'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0968090X21004095?casa_token=8HVnu5TwNUEAAAAA:Xd1y_ol0bzIKDdBls3o5K2fn8BjPebBTJ5OkSHGPVM-c9cvmr9Mr8rWfdih_JHMGwIrHMveR6TI'
citation: 'Yao, R., Zeng, W., Chen, Y., & He, Z. (2021). A deep learning framework for modelling left-turning vehicle behaviour considering diagonal-crossing motorcycle conflicts at mixed-flow intersections. Transportation research part C: emerging technologies, 132, 103415.'
---

[Download paper here](https://www.researchgate.net/publication/355351920_A_deep_learning_framework_for_modelling_left-turning_vehicle_behaviour_considering_diagonal-crossing_motorcycle_conflicts_at_mixed-flow_intersections)

Abstract: With heterogeneous traffic agents moving at unprotected phase, severe crossing conflicts are witnessed at mixed-flow intersections, especially when left-turning vehicles are confronted with motorcycles. However, for modelling vehicle turning behaviour, potential conflicts involving diagonal-crossing motorcycles are seldom investigated in existing studies. To explore these scenes, we present a novel interaction-aware deep-learning framework. Firstly, a Long Short-Term Memory (LSTM) based network is employed to encode vehicle historical motion features. Secondly, each vehicle’s potential target lanes are identified with a probabilistic method, followed by a pooling module that extracts and summarizes intention features. Thirdly, Graph Attention Network (GAT) and a synthesized network are introduced to model vehicle-vehicle interaction and vehicle-motorcycle interaction respectively. Finally, multiple kinds of obtained features are sent to a LSTM based decoder module, where both future displacement and body orientation of vehicles are predicted. In short-time simulation experiments, average displacement error is reduced by 47.7% and 20.0% compared to baseline and state-of-the-art methods, with ablation studies conducted to quantify the efficacy of each kind of feature. Moreover, regarding recursive simulation, our model shows availability of reproducing lane-selecting and motorcycle-evasive behaviours. Distributions of post-encroachment time further indicate that the proposed framework can serve as a promising method to realize reliable motion planning for autonomous vehicles.
