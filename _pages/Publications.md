---
title: ""
permalink: /Publications/
author_profile: true
excerpt: ""
---

[FR: Folded Rationalization with a Unified Encoder. (NeurIPS 2022)](https://arxiv.org/pdf/2209.08285.pdf)
===
- **Task:** Self-explaining rationalization in NLP
- **Problem:** Degeneration. That's to say, in a cooperative game, the predictor and the generator (i.e., rationalizer) may collude to use uninformative rationale candidates to get the right label.
- **Insights:** If the whole model achieves high prediction accuracy, the generator can always learn the true semantic.
- **Solution:** Sharing the encoders between the generator and the predictor, which is very simple and is compatible with many variants of this kind of two-player rationaliser/classifier games. 



[Decoupled Rationalization with Asymmetric Learning Rates: A Flexible Lipschitz Restraint.  (KDD 2023)](https://arxiv.org/abs/2305.13599)
===
- **Task:** Self-explaining rationalization in NLP
- **Problem:** Degeneration. That's to say, in a cooperative game, the predictor and the generator (i.e., rationalizer) may collude to use uninformative rationale candidates to get the right label.
- **Insights:** We first link the degeneration problem to the predictor's Lipschitz continuity. And then we link the predictor's Lipschitz continuity to the coordination of the predictor and the generator.
- **Solution:** Slow down the predictor, which is very simple and is compatible with many variants of this kind of two-player rationaliser/classifier games. 
