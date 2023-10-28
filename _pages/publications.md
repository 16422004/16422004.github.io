---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Feature Synthesis for Few-Shot Object Detection** [pdf](http://16422004.github.io/files/bica.pdf)
---
**Chenchen Tao**, Song Chen, Yi Chen, Xiaojie Cai, Chong Wang<br/>
*BICA*, 2023

<div style="display: flex; align-items: center;">
  <div style="width:50%">
    By combining semantic embeddings with real visual features, the generator
is trained to enhance the correlation between synthetic features and their
corresponding categories. Class prototypes are computed based on real
features, and contrastive loss guides the constraint of synthetic feature
distribution, improving model performance. Additionally, the algorithm
incorporates Pseudo Margin Evaluation loss to calculate instance uncertainty scores and increase discrimination power. E
  </div>
  <div style="width:50%">
    <img src="https://16422004.github.io/images/bica.PNG" alt="bica">
  </div>
</div>

**Action Recognition with Non-Uniform Key Frame Selector** [pdf](http://16422004.github.io/files/ipmv.pdf)
---
Haohe Li, Chong Wang, Shenghao Yu, **Chenchen Tao**<br/>
*IPMV*, 2023

<div style="display: flex; align-items: center;">
  <div style="width:50%">
    A non-uniform key frame selector is proposed to pick the most representative frames according to the relationship between frames along the temporal dimension. Specifically,
the reweight high-level frame features are used to generate an importance score sequence, while the key frames, in each temporal
section, are selected based on the above scores. Such selected frames
have richer semantic information, which has positive impact on the
network training.
  </div>
  <div style="width:50%">
    <img src="https://16422004.github.io/images/ipmv.PNG" alt="IPMV">
  </div>
</div>


**Novel Instance Mining with Pseudo-Margin Evaluation for Few-Shot Object Detection** [pdf](http://16422004.github.io/files/icassp.pdf)<br/>
---
Liu, Weijie, Chong Wang, Shenghao Yu, **Chenchen Tao**, Jun Wang, and Jiafei Wu<br/>
*ICASSP*, 2023

<div style="display: flex; align-items: left;">
  <div style="width：50%">
    A new instance mining model is proposed to excavate the novel samples from the base set. The detector 
    is thus fine-tuned again by these additional free novel 
    instances. Meanwhile, a novel pseudo-margin evaluation
    algorithm is designed to address the quality problem of 
    pseudo-labels brought by those new novel instances.
  </div>
  <div style="width：50%">
    <img src="https://16422004.github.io/images/icassp.PNG" alt="ICASSP">
  </div>
</div>


