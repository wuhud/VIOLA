#  VIOLA: Imitation Learning for Vision-Based Manipulation with Object Proposals Priors
[Yifeng Zhu](https://www.cs.utexas.edu/~yifengz), [Abhishek Joshi]() [Peter Stone](https://www.cs.utexas.edu/~pstone), [Yuke Zhu](https://www.cs.utexas.edu/~yukez/)


[Project](https://ut-austin-rpl.github.io/VIOLA/)  <!-- | [arxiv](http://arxiv.org/abs/2109.13841)  -->


## Introduction
We introduce VIOLA, an object-centric imitation learning approach
to learning closed-loop visuomotor policies for robot manipulation. Our approach
constructs object-centric representations based on general object proposals from a
pre-trained vision model. It uses a transformer-based policy to reason over these
representations and attends to the task-relevant visual factors for action prediction.
Such object-based structural priors improve deep imitation learning algorithm’s
robustness against object variations and environmental perturbations. We quanti-
tatively evaluate VIOLA in simulation and on real robots. VIOLA outperforms
the state-of-the-art imitation learning methods by 45.8% in success rates. It has
also been deployed successfully on a physical robot to solve challenging long-
horizon tasks, such as dining table arrangements and coffee making. More videos
and model details can be found in supplementary materials and the anonymous
project website: [https://sites.google.com/view/viola-manipulation](https://sites.google.com/view/viola-manipulation).
