---
title: "DENet: Disentangled Embedding Network for Visible Watermark Removal"
collection: publications
image: ../files/paper_images/DENET.png
codeurl: https://github.com/lianchengmingjue/DENet
pdfurl: https://ojs.aaai.org/index.php/AAAI/article/view/25337
date: 2023-03-01
author: Ruizhou Sun*, Yukun Su*, Qingyao Wu (* co-first author)
journal: 'Proceedings of the AAAI Conference on Artificial Intelligence (AAAI2023) Oral'
---

Abstract: Adding visible watermark into image is a common copyright protection method of medias. Meanwhile, public research on watermark removal can be utilized as an adversarial technology to help the further development of watermarking. Existing watermark removal methods mainly adopt multi-task learning networks, which locate the watermark and restore the background simultaneously. However, these approaches view the task as an image-to-image reconstruction problem, where they only impose supervision after the final output, making the high-level semantic features shared between different tasks. To this end, inspired by the two-stage coarse-refinement network, we propose a novel contrastive learning mechanism to disentangle the high-level embedding semantic information of the images and watermarks, driving the respective network branch more oriented. Specifically, the proposed mechanism is leveraged for watermark image decomposition, which aims to decouple the clean image and watermark hints in the high-level embedding space. This can guarantee the learning representation of the restored image enjoy more task-specific cues. In addition, we introduce a self-attention-based enhancement module, which promotes the network's ability to capture semantic information among different regions, leading to further improvement on the contrastive learning mechanism. To validate the effectiveness of our proposed method, extensive experiments are conducted on different challenging benchmarks. Experimental evaluations show that our approach can achieve state-of-the-art performance and yield high-quality images.

[Download paper here](https://ojs.aaai.org/index.php/AAAI/article/view/25337)
