---
title: ""
permalink: /Publications/
author_profile: true
excerpt: ""
---

- **Wei Liu**, Zhiying Deng, Zhongyu Niu, Jun Wang, Haozhao Wang, YuanKai Zhang, Ruixuan Li. [Is the MMI Criterion Necessary for Interpretability? Degenerating Non-causal Features to Plain Noise](https://arxiv.org/pdf/2410.06003). In NeurIPS 2024.

**Summary**:  The most widely used criterion for
interpretability is the maximum mutual information (MMI) criterion. However,
in certain datasets, there are spurious features non-causally correlated with the
label and also get high mutual information, complicating the loss landscape of
MMI. Although some penalty-based methods have been developed to penalize the
spurious features (e.g., invariance penalty, intervention penalty, etc) to help MMI
work better, these are merely remedial measures. In the optimization objectives of
these methods, spurious features are still distinguished from plain noise, which hin-
ders the discovery of causal rationales. This paper aims to develop a new criterion
that treats spurious features as plain noise, allowing the model to work on datasets
rich in spurious features as if it were working on clean datasets, thereby making ra-
tionale extraction easier. We theoretically observe that removing either plain noise
or spurious features from the input does not alter the conditional distribution of the
remaining components relative to the task label. However, significant changes in
the conditional distribution occur only when causal features are eliminated. Based
on this discovery, the paper proposes a criterion for Maximizing the Remaining
Discrepancy (MRD). 

- **Wei Liu**, Jun Wang, Haozhao Wang, Ruixuan Li, Yang Qiu, YuanKai Zhang, Jie Han, Yixiong Zou. [Decoupled Rationalization with Asymmetric Learning Rates: A
Flexible Lipschitz Restraint](https://arxiv.org/pdf/2305.13599). In KDD 2023.

**Summary**: A self-explaining rationalization model is generally constructed
by a cooperative game where a generator selects the most human-
intelligible pieces from the input text as rationales, followed by a pre-
dictor that makes predictions based on the selected rationales. How-
ever, such a cooperative game may incur the degeneration problem
where the predictor overfits to the uninformative pieces generated
by a not yet well-trained generator and in turn, leads the generator
to converge to a sub-optimal model that tends to select senseless
pieces. In this paper, we first theoretically link degeneration to the predictor's Lipschitz continuity. Then, we further link the Lipschitz continuity to the two players' learning rates. Finally, we empirically propose a
simple but effective method named DR, which can naturally and
flexibly restrain the Lipschitz constant of the predictor, to address
the problem of degeneration. The main idea of DR is to decouple
the generator and predictor to allocate them with asymmetric learning rates. 

- **Wei Liu**, Jun Wang, Haozhao Wang, Ruixuan Li, Zhiying Deng, YuanKai Zhang, Yang Qiu. [D-Separation for Causal Self-Explanation](https://arxiv.org/pdf/2309.13391). In NeurIPS 2023.
   
**Summary**:  Conventional rationalization methods can be
influenced by spurious features that correlate with the causal rationale or the target
label. Instead of attempting to rectify the issues of traditional methods, we propose a novel criterion to uncover the causal rationale, termed the Minimum Conditional
Dependence (MCD) criterion, which is grounded on our finding that the non-causal
features and the target label are d-separated by the causal rationale. By minimizing
the dependence between the unselected parts of the input and the target label
conditioned on the selected rationale candidate, all the causes of the label are
compelled to be selected. In this study, we employ a simple and practical measure
of dependence, specifically the KL-divergence, to validate our proposed MCD
criterion. 
  



