---
title: "Self-supervised 3D Skeleton Action Representation Learning with Motion Consistency and Continuity"
collection: publications
image: ../files/paper_images/iccv_skeleton.png
pdfurl: https://openaccess.thecvf.com/content/ICCV2021/papers/Su_Self-Supervised_3D_Skeleton_Action_Representation_Learning_With_Motion_Consistency_and_ICCV_2021_paper.pdf
date: 2021-08-01
author: <u>Yukun Su</u>, Guosheng Lin, Qingyao Wu
journal: 'IEEE International Conference on Computer Vision (ICCV2021)'
---

Abstract: Recently, self-supervised learning (SSL) has been proved very effective and it can help boost the performance in learning representations from unlabeled data in the image domain. Yet, very little is explored about its usefulness in 3D skeleton-based action recognition understanding. Directly applying existing SSL techniques for 3D skeleton learning, however, suffers from trivial solutions and imprecise representations. To tackle these drawbacks, we consider perceiving the consistency and continuity of motion at different playback speeds are two critical issues. To this end, we propose a novel SSL method to learn the 3D skeleton representation in an efficacious way. Specifically, by constructing a positive clip (speed-changed) and a negative clip (motion-broken) of the sampled action sequence, we encourage the positive pairs closer while pushing the negative pairs to force the network to learn the intrinsic dynamic motion consistency information. Moreover, to enhance the learning features, skeleton interpolation is further exploited to model the continuity of human skeleton data. To validate the effectiveness of the proposed method, extensive experiments are conducted on Kinetics, NTU60, NTU120, and PKUMMD datasets with several alternative network architectures. Experimental evaluations demonstrate the superiority of our approach and through which, we can gain significant performance improvement without using extra labeled data.

[Download paper here](https://openaccess.thecvf.com/content/ICCV2021/papers/Su_Self-Supervised_3D_Skeleton_Action_Representation_Learning_With_Motion_Consistency_and_ICCV_2021_paper.pdf)

