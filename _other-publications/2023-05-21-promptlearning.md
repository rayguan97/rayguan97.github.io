---
title: "SCP: Soft Conditional Prompt Learning for Aerial Video Action Recognition"
collection: other-publications
permalink: /other-publication/2023-05-21-promptlearning
# excerpt: 'We present an algorithm, Fourier Activity Recognition (FAR), for UAV video activity recognition. Our formulation uses a novel Fourier object disentanglement method to innately separate out the human agent (which is typically small) from the background. Our disentanglement technique operates in the frequency domain to characterize the extent of temporal change of spatial pixels, and exploits convolution-multiplication properties of Fourier transform to map this representation to the corresponding object-background entangled features obtained from the network. To encapsulate contextual information and long-range space-time dependencies, we present a novel Fourier Attention algorithm, which emulates the benefits of self-attention by modeling the weighted outer product in the frequency domain. Our Fourier attention formulation uses much fewer computations than self-attention. We have evaluated our approach on multiple UAV datasets including UAV Human RGB, UAV Human Night, Drone Action, and NEC Drone. We demonstrate a relative improvement of 8.02% - 38.69% in top-1 accuracy and up to 3 times faster over prior works.'
date: 2023-05-21
venue: 'The 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems'
short: 'IROS'
paperurl: 'https://arxiv.org/abs/2305.12437'
teaser: '/images/promptlearning_pipeline.png'
skip: "yes"
# teaser: '../images/tnp_teaser.png'
authors: "Xijun Wang*, Ruiqi Xian*, <b>Tianrui Guan</b>, Fuxiao Liu, Dinesh Manocha"
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---


## Abstract

<div style="text-align: justify">We present a new learning approach, Soft Conditional Prompt Learning (SCP), which leverages the strengths of prompt learning for aerial video action recognition. Our approach is designed to predict the action of each agent by helping the models focus on the descriptions or instructions associated with actions in the input videos for aerial/robot visual perception. Our formulation supports various prompts, including learnable prompts, auxiliary visual information, and large vision models to improve the recognition performance. We present a soft conditional prompt method that learns to dynamically generate prompts from a pool of prompt experts under different video inputs. By sharing the same objective with the task, our proposed SCP can optimize prompts that guide the model's predictions while explicitly learning input-invariant (prompt experts pool) and input-specific (data-dependent) prompt knowledge. In practice, we observe a 3.17-10.2% accuracy improvement on the aerial video datasets (Okutama, NECDrone), which consist of scenes with single-agent and multi-agent actions. We further evaluate our approach on ground camera videos to verify the effectiveness and generalization and achieve a 1.0-3.6% improvement on dataset SSV2. We integrate our method into the ROS2 as well.</div>

<br>

The paper is available [here](https://arxiv.org/abs/2305.12437). Please cite our work if you found it useful,

```
@misc{wang2024scpsoft,
      title={SCP: Soft Conditional Prompt Learning for Aerial Video Action Recognition}, 
      author={Xijun Wang and Ruiqi Xian and Tianrui Guan and Fuxiao Liu and Dinesh Manocha},
      year={2024},
      eprint={2305.12437},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2305.12437}, 
}
```
