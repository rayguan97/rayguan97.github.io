---
title: "AdaptiveON: Adaptive Outdoor Local Navigation Method for Stable and Reliable Actions"
collection: other-publications
permalink: /other-publication/2023-02-01-adaptiveon
# excerpt: 'We present an algorithm, Fourier Activity Recognition (FAR), for UAV video activity recognition. Our formulation uses a novel Fourier object disentanglement method to innately separate out the human agent (which is typically small) from the background. Our disentanglement technique operates in the frequency domain to characterize the extent of temporal change of spatial pixels, and exploits convolution-multiplication properties of Fourier transform to map this representation to the corresponding object-background entangled features obtained from the network. To encapsulate contextual information and long-range space-time dependencies, we present a novel Fourier Attention algorithm, which emulates the benefits of self-attention by modeling the weighted outer product in the frequency domain. Our Fourier attention formulation uses much fewer computations than self-attention. We have evaluated our approach on multiple UAV datasets including UAV Human RGB, UAV Human Night, Drone Action, and NEC Drone. We demonstrate a relative improvement of 8.02% - 38.69% in top-1 accuracy and up to 3 times faster over prior works.'
date: 2023-02-01
venue: 'IEEE Robotics and Automation Letters'
short: 'RA-L'
paperurl: 'https://arxiv.org/abs/2205.03517'
skip: "yes"
# teaser: '../images/tnp_teaser.png'
authors: "Jing Liang, Kasun Weerakoon, <b>Tianrui Guan</b>, Nare Karapetyan, Dinesh Manocha"
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---


## Abstract

<div style="text-align: justify"> We present a novel outdoor navigation algorithm to generate stable and efficient actions to navigate a robot to reach a goal. We use a multi-stage training pipeline and show that our approach produces policies that result in stable and reliable robot navigation on complex terrains. Based on the Proximal Policy Optimization (PPO) algorithm, we developed a novel method to achieve multiple capabilities for outdoor navigation tasks, namely alleviating the robot's drifting, keeping the robot stable on bumpy terrains, avoiding climbing on hills with steep elevation changes, and avoiding collisions. Our training process mitigates the reality (sim-to-real) gap by introducing generalized environmental and robotic parameters and training with rich features of Lidar perception in a high-fidelity Unity simulator. We evaluate our method in both simulation and real world environments using Clearpath Husky and Jackal robots. Further, we compare our method against the state-of-the-art approaches and observe that, in the real world it improves stability by at least 30.7% on uneven terrains, reduces drifting by 8.08% and decreases the elevation changes by 14.75%.</div>

<br>

Please cite our work if you found it useful,

```
@ARTICLE{9991054,
  author={Liang, Jing and Weerakoon, Kasun and Guan, Tianrui and Karapetyan, Nare and Manocha, Dinesh},
  journal={IEEE Robotics and Automation Letters}, 
  title={AdaptiveON: Adaptive Outdoor Local Navigation Method for Stable and Reliable Actions}, 
  year={2023},
  volume={8},
  number={2},
  pages={648-655},
  doi={10.1109/LRA.2022.3229907}}
```
