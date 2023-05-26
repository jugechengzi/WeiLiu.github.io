---
title: "FR: Folded Rationalization with a Unified Encoder"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'We propose a very simple framework for self-explaining rationalization in NLP and beat the SOTA by up to 10.3%.'
paperurl: 'https://arxiv.org/pdf/2209.08285.pdf'
date: 2022-09-20
venue: 'NeurIPS'
---
- **title:** "[FR: Folded Rationalization with a Unified Encoder](https://arxiv.org/pdf/2209.08285.pdf)"
- **Task:** Self-explaining rationalization in NLP
- **Problem:** Degeneration. That's to say, in a cooperative game, the predictor and the generator (i.e., rationalizer) may collude to use uninformative rationale candidates to get the right label.
- **Insights:** If the whole model achieves high prediction accuracy, the generator can always learn the true semantic.
- **Solution:** Sharing the encoders between the generator and the predictor, which is very simple and is compatible with many variants of this kind of two-player rationaliser/classifier games. 
