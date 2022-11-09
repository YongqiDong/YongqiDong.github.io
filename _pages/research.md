---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My ultimate goal is to employ artificial intelligence and interdisciplinary research as tools to shape a better world. For that, I have delved in the transportation domain as the use case. [The essence of transportation is to reconcile the spatio-temporal imbalance in the distribution of matter, information and energy, which is all about time and space](https://www.linkedin.com/pulse/future-autonomous-driving-transportation-science-fiction-yongqi-dong/?trackingId=7Vv1ACfy%2Ftudg0Q5UUXfFA%3D%3D). Thus, I had attach utmost importance to the spatial-temporal correlations in my research.

My current research centers around three main pillars, i.e., Deep Learning for sensing and anomaly detecting, Deep Reinforcement Learning for controlling and decision-making, together with Big Data Analytics for pattern mining.

## Deep Learning for Sensing and Anomaly Detecting
**Sensing---Lane Detection as the Use Case**
- **_Objective_**: To develop robust spatial-temporal neural network model to tackle lane detection in challenging scenes
- **_Delivery_**: Three research papers and one patent

* **A Hybrid Spatial-temporal Deep Learning Architecture for Lane Detection** ([Published on CACIE](https://doi.org/10.1111/mice.12829))
<div align="center">
<video src="https://YongqiDong.github.io/video/NormalSCNN_UNe.mp4" controls="controls" width="599" height="299" loop=true></video> <br/>
Lane detection result testing on tvtLANE dataset
</div> 
<br/>

* **Robust Lane Detection through Self Pre-training with Masked Sequential Autoencoders and Fine-tuning with Customized PolyLoss** (Under view by IEEE-T-ITS and accepted by TRB 2023)
<div align="center">
<img src='/images/normal_result1.jpg' width="879"><br/>
<a href="https://youtu.be/p10oaCRmst0">Lane detection result testing on TUSimple dataset </a>
</div> 
<br/>

* **Sequential Neural Network Model with Spatial-Temporal Attention Mechanism for Robust Lane Detection Using Multi Continuous Image Frames** (Under view by TR_C and accepted by TRB 2023)
<div align="center">
<img src='/images/LLAMAS.png' width="879"><br/>
Lane detection result testing on LLAMAS dataset <br/>
</div> 

<div align="right">
<img src='/images/tvtLANE-Challenging.png' width="909"><br/>
</div> 
<div align="center">
Lane detection result testing on tvtLANE testset #2 (12 challenging situations)<br/>
</div> 
<br/>

**Anomaly Detecting**
* **Comparative Study on Supervised versus Semi-supervised Machine Learning for Anomaly Detection of In-vehicle CAN Network** ([Published on ITSC 2022](https://doi.org/10.1109/ITSC55140.2022.9922235))
<div align="center">
<img src='/images/DAE_Semi_ML_Framework.jpg' width="799"><br/>
Framework of deep autoencoder based semi-supervised method<br/>
</div> 



## Designing Domain-Knowledge-Driven Interpretable Prediction Models
<p style="text-align:center;"><img src="/images/interpretable-prediction.png" width="750" style="margin-top: 0.5em"></p>
Interpretable models ensure that the systems are intelligible for humans at the design stage, which is crucial for <em>high-stakes</em> and <em>safe-critical</em> applications. Therefore, finding interpretable substitutes is a more fundamental solution to ensure transparency, in contrast to explaining black-box deep neural networks. To design interpretable trajectory prediction models, **I investigate principled methods to incorporate domain knowledge of social interaction into prediction models, inducing models reasoning interactive behavior consistently with humans.** Specifically, the proposed methods aim to introduce an interpretable latent space encoding semantically meaningful interactions among the agents. <br/>

<p><b>Related Publications:</b><br>
<font size=3> 1. <b>C. Tang</b>, N. Srishankar, S. Martin and M. Tomizuka, "Grounded Relational Inference: Domain Knowledge-driven Explainable Autonomous Driving," under review for <em>IEEE Transactions on Intelligent Transportation System (T-ITS)</em>, 2022</font><br>
<font size=3> 2. L. Sun<sup>*</sup>, <b>C. Tang</b><sup>*</sup>, Y. Niu, E. Sachdeva, C. Choi, T. Misu, M. Tomizuka, and W. Zhan, “Domain knowledge driven pseudo labels for interpretable goal-conditioned interactive trajectory prediction,” <em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</em>, 2022</font><br></p>
  
## Designing Interpretable Hierarchical Driving Policys
<p style="text-align:center;"><img src="/images/interpretable-policy.png" width="720" style="margin-top: 0.5em"></p>
Another line of my research on interpretability studies interpretable driving policies. **I explored hierarchical architectures with interpretable intermediate outputs to reveal the decision-making process**. In particular, I am interested in driving policies with *trajectories* as intermediate outputs. The trajectory indicates a sequence of future states the policy aims to achieve, which implies the intended driving behavior of the policy. It helps the users better understand the decision-making process. Furthermore, such a hierarchical structure decomposes the policy into 1) a *high-level* module that plans the desired behavior represented by a trajectory; 2) a *low-level* module that realizes the desired behavior by controlling the vehicles. It allows flexible composition of different approaches when designing hierarchical policies. In particular, we showed that we could improve robustness or long-term performance by fusing learning-based (e.g., reinforcement learning, imitation learning) and model-based (e.g., robust control, optimal control) approaches in the hierarchy. 

<p><b>Related Publications:</b><br>
<font size=3> 1. Z. Xu<sup>*</sup>, <b>C. Tang</b><sup>*</sup>, and M. Tomizuka, “Zero-shot Deep Reinforcement Learning Driving Policy Transfer for Autonomous Vehicles based on Robust Control,” <em>IEEE International Conference on Intelligent Transportation Systems (ITSC)</em>, 2018 </font><br>
<font size=3> 2. <b>C. Tang</b><sup>*</sup>, Z. Xu<sup>*</sup>, and M. Tomizuka, "Disturbance-Observer-Based Tracking Controller for Neural Network Driving Policy Transfer," <em>IEEE Transactions on Intelligent Transportation Systems</em>, 2020 </font><br>
<font size=3> 3. J. Li, <b>C. Tang</b>, W. Zhan, and M. Tomizuka, “Hierarchical planning through goal-conditioned offline reinforcement learning,” <em>IEEE Robotics and Automation Letters (RA-L)</em> and <em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</em>, 2022 </font><br></p>
 
## Improve Robustness of Learning-based Methods 
In addition to transparency, some of my prior works listed above also improve the robustness of behavior prediction models and policy networks. For behavior prediction, one crucial aspect is designing the model architecture and training scheme to induce a generalizable scene representation (e.g., map, social context). For policy networks, one crucial aspect is dealing with external disturbances and modeling discrepancies. Please find a list of related publications below. 

<p><b>Related Publications:</b><br>
<font size=3> 1. Z. Xu<sup>*</sup>, <b>C. Tang</b><sup>*</sup>, and M. Tomizuka, “Zero-shot Deep Reinforcement Learning Driving Policy Transfer for Autonomous Vehicles based on Robust Control,” <em>IEEE International Conference on Intelligent Transportation Systems (ITSC)</em>, 2018 </font><br>
<font size=3> 2. <b>C. Tang</b><sup>*</sup>, Z. Xu<sup>*</sup>, and M. Tomizuka, "Disturbance-Observer-Based Tracking Controller for Neural Network Driving Policy Transfer," <em>IEEE Transactions on Intelligent Transportation Systems</em>, 2020 </font><br>
<font size=3> 3. <b>C. Tang</b>, W. Zhan and M. Tomizuka, "Exploring Social Posterior Collapse in Variational Autoencoder for Interaction Modeling," <em>Conference on Neural Information Processing Systems (NeurIPS)</em>, 2021</font><br>
<font size=3> 4. J. Li, <b>C. Tang</b>, W. Zhan, and M. Tomizuka, "Dealing with the unkonw: Pessimistic Offline Reinforcement Learning," <em>5th Annual Conference on Robot Learning (CoRL)</em>, 2022 </font><br>
<font size=3> 5. J. Li, <b>C. Tang</b>, W. Zhan, and M. Tomizuka, “Hierarchical planning through goal-conditioned offline reinforcement learning,” <em>IEEE Robotics and Automation Letters (RA-L)</em> and <em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</em>, 2022 </font><br>
<font size=3> 6. C. Xu<sup>*</sup>, T. Li<sup>*</sup>, <b>C. Tang</b><sup>*</sup>, L. Sun, K. Keutzer, M. Tomizuka, A. Fathi, and W. Zhan, "PreTraM: Self-Supervised Pre-training via Connecting Trajectory and Map," <em>European Conference on Computer Vision (ECCV)</em>, 2022 </font><br></p>
 
