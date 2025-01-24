---
title: ""
permalink: /Publications/
author_profile: true
excerpt: ""
---

<div style="margin-bottom: 20px; overflow: hidden;">
    <h3 style="margin: 0;">1FR: Folded Rationalization with a Unified Encoder (NeurIPS 2022).</h3>
    <p style="margin: 5px 0 10px;">Authors: <b>Wei Liu</b>, Haozhao Wang, Jun Wang, Ruixuan Li, Chao Yue, Yuankai Zhang </p>
    <p style="margin: 5px 0 10px;"><b>Task</b>: Self-explaining rationalization in NLP.</p>
    <p style="margin: 5px 0 10px;"><b>Problem</b>: Degeneration. That's to say, in a cooperative game, the predictor and the generator (i.e., rationalizer) may collude to use uninformative rationale candidates to get the right label.</p>
    <p style="margin: 5px 0 10px;"><b>Insights</b>: If the whole model achieves high prediction accuracy, the generator can always learn the true semantic. </p>
    <p style="margin: 5px 0 10px;"><b>Solution</b>: Sharing the encoders between the generator and the predictor, which is very simple and is compatible with many variants of this kind of two-player rationaliser/classifier games. </p>
  <img src="../images/neurips22.png" alt="test2" style="width: 600px; height: auto; margin-top: 20px; display: block; border-radius: 5px;">
</div>


<iframe 
    src="https://www.youtube.com/watch?v=we-IvfxuDuU" 
    width="560" 
    height="315" 
    frameborder="0" 
    allow="autoplay; fullscreen; picture-in-picture" 
    allowfullscreen>
</iframe>

[Decoupled Rationalization with Asymmetric Learning Rates: A Flexible Lipschitz Restraint.  (KDD 2023)](https://arxiv.org/abs/2305.13599)
===
- **Task:** Self-explaining rationalization in NLP
- **Problem:** Degeneration. That's to say, in a cooperative game, the predictor and the generator (i.e., rationalizer) may collude to use uninformative rationale candidates to get the right label.
- **Insights:** We first link the degeneration problem to the predictor's Lipschitz continuity. And then we link the predictor's Lipschitz continuity to the coordination of the predictor and the generator.
- **Solution:** Slow down the predictor, which is very simple and is compatible with many variants of this kind of two-player rationaliser/classifier games.

MGR: Multi-generator Based Rationalization
===
- **Task:** Causal discovery from a perspective of causal feature selection
- **Problem:** Previous causal discovery methods usually involve many assumptions for causal inference (e.g., the conditional independence assumed by a graphical model, and the ignorability of a SCM).
- **Insights:** We provide some insights into how to select causal features from a purely probabilistic perspective, which doesn't involve the above assumptions.

  



