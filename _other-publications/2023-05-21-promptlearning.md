---
title: "Prompt Learning for Action Recognition"
collection: other-publications
permalink: /other-publication/2023-05-21-promptlearning
# excerpt: 'We present an algorithm, Fourier Activity Recognition (FAR), for UAV video activity recognition. Our formulation uses a novel Fourier object disentanglement method to innately separate out the human agent (which is typically small) from the background. Our disentanglement technique operates in the frequency domain to characterize the extent of temporal change of spatial pixels, and exploits convolution-multiplication properties of Fourier transform to map this representation to the corresponding object-background entangled features obtained from the network. To encapsulate contextual information and long-range space-time dependencies, we present a novel Fourier Attention algorithm, which emulates the benefits of self-attention by modeling the weighted outer product in the frequency domain. Our Fourier attention formulation uses much fewer computations than self-attention. We have evaluated our approach on multiple UAV datasets including UAV Human RGB, UAV Human Night, Drone Action, and NEC Drone. We demonstrate a relative improvement of 8.02% - 38.69% in top-1 accuracy and up to 3 times faster over prior works.'
date: 2023-05-21
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2305.12437'
skip: "yes"
# teaser: '../images/tnp_teaser.png'
authors: "Xijun Wang*, Ruiqi Xian*, <b>Tianrui Guan</b>, Dinesh Manocha"
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---


## Abstract

<div style="text-align: justify">We present a new general learning approach for action recognition, Prompt Learning for Action Recognition (PLAR), which leverages the strengths of prompt learning to guide the learning process. Our approach is designed to predict the action label by helping the models focus on the descriptions or instructions associated with actions in the input videos. Our formulation uses various prompts, including optical flow, large vision models, and learnable prompts to improve the recognition performance. Moreover, we propose a learnable prompt method that learns to dynamically generate prompts from a pool of prompt experts under different inputs. By sharing the same objective, our proposed PLAR can optimize prompts that guide the model's predictions while explicitly learning input-invariant (prompt experts pool) and input-specific (data-dependent) prompt knowledge. We evaluate our approach on datasets consisting of both ground camera videos and aerial videos, and scenes with single-agent and multi-agent actions. In practice, we observe a 3.17-10.2% accuracy improvement on the aerial multi-agent dataset, Okutamam and 0.8-2.6% improvement on the ground camera single-agent dataset, Something Something V2.</div>

<br>

Please cite our work if you found it useful,

```
@misc{wang2023prompt,
      title={Prompt Learning for Action Recognition}, 
      author={Xijun Wang and Ruiqi Xian and Tianrui Guan and Dinesh Manocha},
      year={2023},
      eprint={2305.12437},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
