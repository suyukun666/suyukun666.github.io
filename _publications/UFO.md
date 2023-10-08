---
title: "A unified transformer framework for group-based segmentation: Co-segmentation, co-saliency detection and video salient object detection"
collection: publications
image: ../files/paper_images/UFO.png
codeurl: https://github.com/suyukun666/UFO
demourl: https://huggingface.co/spaces/djl234/UFO
pdfurl: https://arxiv.org/abs/2203.04708v2
date: 2023-06-01
author: <u>Yukun Su</u>, Jingliang Deng, Ruizhou Sun, Guosheng Lin, Qingyao Wu
journal: 'IEEE Transactions on Multimedia (TMM2023)'
---

Abstract: Humans tend to mine objects by learning from a group of images or several frames of video since we live in a dynamic world. In the computer vision area, many researches focus on co-segmentation (CoS), co-saliency detection (CoSD) and video salient object detection (VSOD) to discover the co-occurrent objects. However, previous approaches design different networks on these similar tasks separately, and they are difficult to apply to each other, which lowers the upper bound of the transferability of deep learning frameworks. Besides, they fail to take full advantage of the cues among inter- and intra-feature within a group of images. In this paper, we introduce a unified framework to tackle these issues, term as UFO (Unified Framework for Co-Object Segmentation). Specifically, we first introduce a transformer block, which views the image feature as a patch token and then captures their long-range dependencies through the self-attention mechanism. This can help the network to excavate the patch structured similarities among the relevant objects. Furthermore, we propose an intra-MLP learning module to produce self-mask to enhance the network to avoid partial activation. Extensive experiments on four CoS benchmarks (PASCAL, iCoseg, Internet and MSRC), three CoSD benchmarks (Cosal2015, CoSOD3k, and CocA) and four VSOD benchmarks (DAVIS16, FBMS, ViSal and SegV2) show that our method outperforms other state-of-the-arts on three different tasks in both accuracy and speed by using the same network architecture , which can reach 140 FPS in real-time.

[Download paper here](https://arxiv.org/abs/2203.04708v2)

