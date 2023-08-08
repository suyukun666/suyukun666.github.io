---
title: "Robust network architecture search via feature distortion restraining"
collection: publications
permalink: /publication/RNAS
# excerpt:
date: 2022-08-01
venue: 'European Conference on Computer Vision (ECCV)'
# paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-20065-6_8'
citation: 'Qian Y, Huang S, Wang B, et al. Robust network architecture search via feature distortion restraining[C]//European Conference on Computer Vision. Cham: Springer Nature Switzerland, 2022: 122-138.'
---


Abstract: The vulnerability of Deep Neural Networks, i.e., susceptibility to adversarial attacks, severely limits the application of DNNs in security-sensitive domains. Most of existing methods improve model robustness from weight optimization, such as adversarial training. However, the architecture of DNNs is also a key factor to robustness, which is often neglected or underestimated. We propose Robust Network Architecture Search (RNAS) to obtain a robust network against adversarial attacks. We observe that an adversarial perturbation distorting the non-robust features in latent feature space can further aggravate misclassification. Based on this observation, we search the robust architecture through restricting feature distortion in the search process. Specifically, we define a network vulnerability metric based on feature distortion as a constraint in the search process. This process is modeled as a multi-objective bilevel optimization problem and a novel algorithm is proposed to solve this optimization. Extensive experiments conducted on CIFAR-10/100 and SVHN show that RNAS achieves the best robustness under various adversarial attacks compared with extensive baselines and SOTA methods.

[Download paper here](https://link.springer.com/chapter/10.1007/978-3-031-20065-6_8)