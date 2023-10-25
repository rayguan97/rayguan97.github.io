---
title: "HallusionBench: You See What You Think? Or You Think What You See? An Image-Context Reasoning Benchmark Challenging for GPT-4V(ision), LLaVA-1.5, and Other Multi-modality Models"
collection: publications
permalink: /publication/2023-10-24-hallusion
excerpt: 'Large language models (LLMs), after being aligned with vision models and integrated into vision-language models (VLMs), can bring impressive improvement in image reasoning tasks. This was shown by the recently released GPT-4V(ison), LLaVA-1.5, etc. However, the strong language prior in these SOTA LVLMs can be a double-edged sword: they may ignore the image context and solely rely on the (even contradictory) language prior for reasoning. In contrast, the vision modules in VLMs are weaker than LLMs and may result in misleading visual representations, which are then translated to confident mistakes by LLMs. To study these two types of VLM mistakes, i.e., language hallucination and visual illusion, we curated HallusionBench, an image-context reasoning benchmark that is still challenging to even GPT-4V and LLaVA-1.5. We provide a detailed analysis of examples in HallusionBench, which sheds novel insights on the illusion or hallucination of VLMs and how to improve them in the future. The benchmark and codebase will be released.'
date: 2023-10-24
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2310.14566'
teaser: '../images/hallusion_teaser.png'
authors: "Fuxiao Liu*, <b>Tianrui Guan*</b>, Zongxia Li, Lichang Chen, Yaser Yacoob, Dinesh Manocha, Tianyi Zhou"
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
code: "https://github.com/tianyi-lab/HallusionBench"
redirect_from: 
  - /hallusion
---

<p style="text-align:center;">
<img src="../images/hallusion_fig.png" width="800">
</p>

## Abstract
<div style="text-align: justify"> Large language models (LLMs), after being aligned with vision models and integrated into vision-language models (VLMs), can bring impressive improvement in image reasoning tasks. This was shown by the recently released GPT-4V(ison), LLaVA-1.5, etc. However, the strong language prior in these SOTA LVLMs can be a double-edged sword: they may ignore the image context and solely rely on the (even contradictory) language prior for reasoning. In contrast, the vision modules in VLMs are weaker than LLMs and may result in misleading visual representations, which are then translated to confident mistakes by LLMs. To study these two types of VLM mistakes, i.e., language hallucination and visual illusion, we curated HallusionBench, an image-context reasoning benchmark that is still challenging to even GPT-4V and LLaVA-1.5. We provide a detailed analysis of examples in HallusionBench, which sheds novel insights on the illusion or hallucination of VLMs and how to improve them in the future. The benchmark and codebase will be released. </div>
<br>


|Paper|Code| 
|---|---|
|[**HallusionBench**](https://arxiv.org/abs/2310.14566) | [**GitHub Code**](https://github.com/tianyi-lab/HallusionBench)| 

<br>

Please cite our work if you found it useful,

```
@misc{liu2023hallusionbench,
      title={HallusionBench: You See What You Think? Or You Think What You See? An Image-Context Reasoning Benchmark Challenging for GPT-4V(ision), LLaVA-1.5, and Other Multi-modality Models}, 
      author={Fuxiao Liu and Tianrui Guan and Zongxia Li and Lichang Chen and Yaser Yacoob and Dinesh Manocha and Tianyi Zhou},
      year={2023},
      eprint={2310.14566},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
