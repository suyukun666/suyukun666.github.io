---
title: "Self-Supervised Object Localization with Joint Graph Partition"
collection: publications
image: ../files/paper_images/AAAI22.png
pdfurl: https://ojs.aaai.org/index.php/AAAI/article/view/20127
date: 2022-03-01
author: Yukun Su, Guosheng Lin, Qingyao Wu
journal: 'Proceedings of the AAAI Conference on Artificial Intelligence (AAAI2022)'
---

Abstract: Object localization aims to generate a tight bounding box for the target object, which is a challenging problem that has been deeply studied in recent years. Since collecting bounding-box labels is time-consuming and laborious, many researchers focus on weakly supervised object localization (WSOL). As the recent appealing self-supervised learning technique shows its powerful function in visual tasks, in this paper, we take the early attempt to explore unsupervised object localization by self-supervision. Specifically, we adopt different geometric transformations to image and utilize their parameters as pseudo labels for self-supervised learning. Then, the class-agnostic activation map (CAAM) is used to highlight the target object potential regions. However, such attention maps merely focus on the most discriminative part of the objects, which will affect the quality of the predicted bounding box. Based on the motivation that the activation maps of different transformations of the same image should be equivariant, we further design a siamese network that encodes the paired images and propose a joint graph cluster partition mechanism in an unsupervised manner to enhance the object co-occurrent regions. To validate the effectiveness of the proposed method, extensive experiments are conducted on CUB-200-2011, Stanford Cars and FGVC-Aircraft datasets. Experimental results show that our method outperforms state-of-the-art methods using the same level of supervision, even outperforms some weakly-supervised methods.

[Download paper here](https://ojs.aaai.org/index.php/AAAI/article/view/20127)
