---
layout: post
title: Occlusion-Robust 3d Hand Mesh Estimation Network, CVPR, 2022.
date: 2022-06-19 13:32:20 +0300
description:  CVPR, 2022. # Add post description (optional)
img: handoccnet2.gif # handoccnet.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [3D hands, 3D humans, Occlusion-robust network]
---
##### Joonkyu Park, Yeonguk Oh, Gyeongsik Moon, Hongsuk Choi, and Kyoung Mu Lee
Hands are often severely occluded by objects, which makes 3D hand mesh estimation challenging.
Previous works often have disregarded information at occluded regions.
However, we argue that occluded regions have strong correlations with hands so that they can provide highly beneficial information for complete 3D hand mesh estimation.
Thus, in this work, we propose a novel 3D hand mesh estimation network HandOccNet, that can fully exploits the information at occluded regions as a secondary means to enhance image features and make it much richer.
To this end, we design two successive Transformer-based modules, called feature injecting transformer (FIT) and self-enhancing transformer (SET).
FIT injects hand information into occluded region by considering their correlation.
SET refines the output of FIT by using a self-attention mechanism.
By injecting the hand information to the occluded region, our HandOccNet reaches the state-of-the-art performance on 3D hand mesh benchmarks that contain challenging hand-object occlusions. [[paper](https://arxiv.org/abs/2203.14564)]
