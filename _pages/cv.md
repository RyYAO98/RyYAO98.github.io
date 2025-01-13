---
layout: archive
title: # "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. Candidate in Robotics and Autonomous Systems, The Hong Kong University of Science and Technology (Guangzhou), 2022-*present*

* B.Eng. in Automation, Guangdong University of Technology, 2017-2021
  * GPA: 90.76/100, Ranking in the Major: 1/196

Publications/Working papers
======
* **Yao, R.**, Wang, Y., Liu, H., Yang, R., Peng, Z., Zhu, L., & Ma, J.\* (2024). CALMM-Drive: Confidence-Aware Autonomous Driving with Large Multimodal Model. arXiv preprint arXiv:2412.04209.[[link](https://arxiv.org/abs/2412.04209)]

* Liu, H., **Yao, R.**, Huang, Z., Shen, S., & Ma, J.\* (2024). LMMCoDrive: Cooperative Driving with Large Multimodal Model. arXiv preprint arXiv:2409.11981.[[link](https://arxiv.org/abs/2409.11981)]

* **Yao, R.**, & Sun, X.\* (2025). Hierarchical prediction uncertainty-aware motion planning for autonomous driving in lane-changing scenarios. Transportation Research Part C: Emerging Technologies, 171, 104962.[[link](https://www.sciencedirect.com/science/article/pii/S0968090X24004832)]

* **Yao, R.**, & Sun, X.\* (2024, June). Hierarchical Uncertainty-aware Autonomous Driving in Lane-changing Scenarios: Behavior Prediction and Motion Planning. In 2024 IEEE Intelligent Vehicles Symposium (IV) (pp. 715-721). IEEE.[[link](https://ieeexplore.ieee.org/abstract/document/10588739?casa_token=7USZ_-HCQKQAAAAA:8ZIXXdekEba2UFFe0eq16kJSBv-UbrG3P-0fXbPbPmNqagbRBp1WgN3Zpd0QYvAWS63YyS85oalx)]

* Lin, Z., He, Z.\*, **Yao, R.**, Wang, X., Liu, T., Deng, Y., & Xie, S. (2022). Deep dual attention network for precise diagnosis of covid-19 from chest ct images. IEEE Transactions on Artificial Intelligence. [[link](https://ieeexplore.ieee.org/abstract/document/9965606?casa_token=1YA5Dal6dGUAAAAA:VTT0zr6uE6-kgGUJYoEMLy5EyEVd2LNQ0WCjsIPttDPs1kwI41yAqayR8YCZf5df0iyA9JMbpywW2A)]

* **Yao, R.**, Zeng, W.\*, Chen, Y., & He, Z. (2021). A deep learning framework for modelling left-turning vehicle behaviour considering diagonal-crossing motorcycle conflicts at mixed-flow intersections. *Transportation research part C: emerging technologies*, 132, 103415. \[[link](https://www.sciencedirect.com/science/article/pii/S0968090X21004095?casa_token=8HVnu5TwNUEAAAAA:Xd1y_ol0bzIKDdBls3o5K2fn8BjPebBTJ5OkSHGPVM-c9cvmr9Mr8rWfdih_JHMGwIrHMveR6TI)\]

Research Experience
======
* **Confidence-Aware Autonomous Driving with Large Multimodal Model, 2024.02-2024.11**
  * Position: PhD Student, Advisor: Prof. Jun MA
  * (Coming soon...)

* **Uncertainty-aware Autonomous Driving in Lane-changing Scenarios, 2022.09-2023.12**
  * Position: PhD Student, Advisor: Prof. Xiaotong SUN
  * Developed a two-dimensional behavior prediction and motion planning pipeline for implementing autonomous driving in lane-changing scenarios, with a specialty of tackling behavior prediction uncertainties for enhancing planning safety.
  * A deep learning-based model is proposed to predict lane-changing intention and intention-conditioned future trajectories in a hierarchical and stochastic manner.
  * A discrete-time finite-horizon motion planning problem is formulated, where non-Gaussian safety constraints are constructed with higher-level intention uncertainty and lower-level trajectory uncertainty in the prediction outputs. Three different schemes are investigated to address the intention uncertainty with respective preferences on the expectation, robustness and adaptiveness, while the trajectory uncertainty is handled using a chance constraint formulation.
  * The planning problem is solved via our improved CILQR algorithm that employs soft and hard barrier functions in separate optimization stages.
  * Evaluations using INTERACTION and HighD datasets demonstrate the safety performance of the uncertainty-aware planning pipeline.

* **Federated Learning for Generalizable Traffic Simulation, 2022.03-2022.07**
  * Position: Research Assistant, Advisor: Prof. Zhaoshui HE
  * Independently implemented trajectory-prediction backbone VectorNet on INTERACTION benchmark.
  * Developed a federated learning scheme for improving the generalizability of deep learning models when applied to traffic simulation in multiple variant sites.

* **Deep Learning for COVID-19 Detection with CT Images, 2021.06-2022.02**
  * Position: Research Assistant, Advisor: Prof. Zhaoshui HE
  * Explored the availability of ResNet50, DenseNet161, EfficientNet-B7 and GhostNet on four COVID-19 classification benchmarks (e.g. COVIDx-CT, HUST-19).
  * Cooperated in proposing sample separation strategy that converts the conventional training into a two-stage training, boosted the accuracy by up to 9.46% on a single model.
  * Assisted in revising and implementing the Deep Dual Attention Network for COVID-19 detection from CT images.

* **Modeling and Simulation of Dynamic Shared Autonomous Taxi Dispatching System, 2019.07-2021.02**
  * Position: Research Assistant, Advisor: Prof. Weiliang ZENG
  * Independently proposed deep learning framework DIIA-Net for modelling vehicle turning behaviour at mixed-flow intersections.
  * A LSTM-based network is employed to encode vehicle historical motion features. Then, each vehicle’s potential target lanes are identified with a probabilistic method, followed by a pooling module to extract dynamic intention features. GAT and a synthesized network are introduced to model homogeneous interaction and heterogeneous interaction respectively. Finally, multiple kinds of obtained features are sent to a LSTM-based decoder, where both future displacement and body orientation are generated.
  * Independently implemented the proposed network with PyTorch framework, which achieved state-of-the-art performance compared with En-Dec baseline, VP-LSTM and Conv-LSTM.

Selected Honors & Awards
======
* Outstanding Undergraduate Thesis Award, 2021
* Academic Outstanding Scholarship (twice), 2019 & 2020
* First-class Excellent Student Scholarship, 2020
* Second-class Excellent Student Scholarship (twice), 2018 & 2019

Professional Services
======
* Reviewer: IEEE IROS
* Teaching Assistant: HKUST(GZ) ROAS60OOI - Optimal Control Systems (Instructor: Prof. Jun MA), HKUST(GZ) INTR5210 - Game Theoretical Methods in Transportation (Instructor: Prof. Xiaotong SUN)

Standard Language Test
======
* IELTS 7.0 (R-8.5, L-7.5, S-6.0, W-6.5), Nov. 2021
* IELTS 7.0 (R-8.0, L-8.0, S-6.5, W-6.0), Aug. 2019

Computer Skills
======
* Programming Languages: Python, C
* Machine Learning & Optimization Frameworks: PyTorch, NumPy, OpenAI Gym, CVXPY, GAMS

*updated in JAN. 2025*
