---
layout: archive
title: "Research Overview"
permalink: /research/
author_profile: true
---

My ultimate goal is to employ artificial intelligence and interdisciplinary research as tools to shape a better world. For that, I have delved into the transportation domain as the use case. [The essence of transportation is to reconcile the spatio-temporal imbalance in the distribution of matter, information and energy, which is all about time and space](https://www.linkedin.com/pulse/future-autonomous-driving-transportation-science-fiction-yongqi-dong/?trackingId=7Vv1ACfy%2Ftudg0Q5UUXfFA%3D%3D). Thus, I had attached the utmost importance to the spatial-temporal correlations in my research.

My current research centers around three main pillars, i.e., 
1) **Deep Learning for sensing and anomaly detecting**,
2) **Deep Reinforcement Learning for controlling and decision-making**,
3) **Big Data Analytics for spatial-temporal pattern mining**.

## Deep Learning for Sensing and Anomaly Detecting
**Sensing---Lane Detection as the Case Study**
- **_Objective_**: To develop robust spatial-temporal neural network model to tackle lane detection in challenging scenes
- **_Delivery_**: **Three** research papers, **one patent**, and **one software registration**

* **A Hybrid Spatial-temporal Deep Learning Architecture for Lane Detection** ([Published on CACIE](https://doi.org/10.1111/mice.12829))
<div align="center">
<img src='/images/CACIE-ST-NN.png' width="879"><br/>
The architecture of the proposed hybrid spatial-temporal sequence-to-one spatial-temporal neural network model
</div> 
<br/>

<div align="center">
<video src="https://YongqiDong.github.io/video/NormalSCNN_UNe.mp4" controls="controls" width="599" height="299" loop=true></video> <br/>
Lane detection result testing on tvtLANE dataset
</div> 


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
Lane detection result testing on tvtLANE test set #2 (12 challenging situations)<br/>
</div> 
<br/>

**Anomaly Detecting**
* **Comparative Study on Supervised versus Semi-supervised Machine Learning for Anomaly Detection of In-vehicle CAN Network** ([Published on ITSC 2022](https://doi.org/10.1109/ITSC55140.2022.9922235)) [Recorded Video Presentation](https://youtu.be/melrgznLXP0)
<div align="center">
<img src='/images/DAE_Semi_ML_Framework.jpg' width="799"><br/>
Framework of deep autoencoder based semi-supervised method<br/><br/>
<img src='/images/CAN_AnomalyDetectionResults.png' width="799"><br/>
CAN Bus data anomaly detection results: model performance comparison<br/>
</div> 

<br/>

* **Intelligent Anomaly Detection for Lane Rendering Using Transformer with Self-Supervised Pre-Training and Customized Fine-Tuning** (Under view by Journal of Intelligent and Connected Vehicles and CICTP 2023)<br/>
  - Objective: To efficiently detect whether there are defects in the rendered generated map data for navigation
  - Developed and implemented a 4-phase pipeline incorporating data pre-processing, self-supervised pre-training with the masked image modelling (MiM) method, customized fine-tuning with cross-entropy loss (or its variants), and post-processing


## Deep Reinforcement Learning for Controlling and Decision-making

* **Towards Developing Socially-Compliant Automated Vehicles: State of the Practice, Experts Expectations, and a Conceptual Framework** (To be submitted to Journal of Transport Reviews, and accepted by MFTS2022)

* **Social-aware Planning and Control for Automated Vehicles based on Driving Risk Field and Model Predictive Contouring Control: Driving through Roundabouts as a Case Study** (Accepted by IEEE SMC 2023, [Demo video](https://youtu.be/XLpwgmsyg_M))
<div align="center">
<video src="https://YongqiDong.github.io/video/SupplementaryVideo-SMCSocialAwareDrivingThroughRoundabout.mp4" controls="controls" width="936" height="521" loop=true></video> <br/>
Social-aware Planning and Control for Automated Vehicles based on DRF-SVO-MPCC
</div> 

* **Comprehensive Comparison of Deep Reinforcement Learning for Automated Driving on Various Driving Maneuvers with Simulation** (Under Review by _the 26th IEEE International Conference on Intelligent Transportation Systems_, ITSC 2023), [Preprint](https://arxiv.org/abs/2306.11466).
* **Safe, Efficient, Comfort, and Energy-saving Automated Driving through Roundabout Based on Deep Reinforcement Learning** (Under Review by _the 26th IEEE International Conference on Intelligent Transportation Systems_, ITSC 2023), [Preprint](https://arxiv.org/abs/2306.11465).

<br/>
  
## Big Data Analytics for Spatial-temporal Pattern Mining in Shared Mobility
* **An Empirical Study on Travel Patterns of Internet Based Ride-Sharing** ([Published on TR_C](https://doi.org/10.1016/j.trc.2017.10.022))<br/>
  - On-demand ride-sharing is quite different from taxi<br/>
  - In Beijing, on the macrocosmic level, on-demand ride-sharing mainly serves as an approach for home-work commuting<br/>
  - Internet-based on-demand ride-sharing drivers intend to make longer trips than taxi, and detour further to pick up passengers than hitchhike drivers<br/>
**Regarding Individual Behavior Patterns of Ride-sharing Drivers**
    - Two different categories are identified: the home-work commuting drivers and the random commuting drivers; 
    - Counterintuitively, the home-work commuting ones account for only a small part of the total drivers
    - There is high probability to be classified into the home-work commuting category when less trips are served by the specific driver
    - Results support and are in line with policy-making
    
<div align="center">
<img src='/images/taxi_pickup.gif' width="309" height="309"> <img src='/images/Ridesharing_pick.gif' width="309" height="309"> <img src='/images/fastcarpick.gif' width="309" height="309"/><br/>
<img src='/images/taxi_drop.gif' width="309" height="309" margin-top="6px"> <img src='/images/Ridesharing_drop.gif' width="309" height="309" margin-top="6px"> <img src='/images/fastcardrop.gif' width="309" height="309" margin-top="6px" /><br/>
Dynamic spatial-temporal service patterns
</div> 
<br/>

* **Revealing Travel Patterns of Sharing-bikes in a Spatial-temporal Manner using Non-negative Matrix Factorization Method** ([Published in CICTP 2018](https://doi.org/10.1061/9780784481523.165))<br/>
  - Sharing bikes provide short-distance travel services around subway stations with three peaks<br/>
  - Bike-sharing could be expressed by three (or five) basis collective patterns which differ from ride-sharing of two collective patterns<br/>
  - NMF method is more appropriate than PCA in extracting spatial-temporal patterns in transportation research 

<div align="center">
<img src='/images/BikeSharing.png' width="799"><br/>
Extracted basis collective patterns of bike-sharing by non-negative matrix factorization<br/>
</div> 


<br/>
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=698&t=tt&d=linXdGUW0uzldsSGTUU1wkce_m9BE5xmEZBiDgTGM9w'></script>
