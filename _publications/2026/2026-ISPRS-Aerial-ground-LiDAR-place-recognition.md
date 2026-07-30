---
title:          'Aerial-ground LiDAR place recognition with patch-level self-supervised learning and expanded reciprocal re-ranking'
date:           2026-07-30 00:01:00 +0800
selected:       true
pub:            "‌ISPRS Journal of Photogrammetry and Remote Sensing (IF: 12.2)"
pub_date:       "2026"
abstract: >-
   LiDAR place recognition determines one's position on a prior point cloud map. The most studied ground-level LiDAR place recognition suffers from pre-visit requirements, incomplete coverage, and limited perspectives. Using pre-acquired, full-coverage Airborne Laser Scanning (ALS) data as an aerial prior map overcomes these drawbacks, making cross-view place recognition necessary and advantageous. However, aerial-ground LiDAR place recognition faces significant challenges, including the domain gap between aerial and ground point clouds, and false positives during initial retrieval. To address these challenges, we present a novel retrieval and re-ranking framework for aerial-ground LiDAR place recognition. Based on the priors that neighboring point cloud patches share similar semantics with anchor patch, our retrieval network introduces patch-level self-supervised learning modules at multiple scales and integrates with scene-level learning to improve global feature discriminativeness between aerial and ground point clouds. Furthermore, leveraging the structured spatial distribution of ALS point clouds, we introduce an Expanded Reciprocal (ER) re-ranking algorithm to exploit neighborhood information maximally and refine each feature based on neighbor features, which are then used to update the similarity matrix for final ranking. Extensive experiments demonstrate that our retrieval network outperforms existing state-of-the-art (SOTA) methods, achieving a 9.8% improvement in average Recall@1 and a 3.2% improvement in average Recall@1% on the CS-Urban-Scenes, while also showing the best performance on the CS-Campus3D dataset. Additionally, our ER re-ranking algorithm further boosts the average Recall@1 by 4.9% on CS-Campus3D and 10.2% on CS-Urban-Scenes without additional training.

cover:          assets/images/covers/AG-PCPR.png
authors:
  - Yandi Yang
  - Xianghong Zou†
  - Jianping Li
  - Haofeng Xie
  - Saurav Uprety
  - Hongzhou Yang
  - Naser El-Sheimy

links:
  Project: [None](https://)
  Papar: [https://arxiv.org/abs/2606.18583](https://arxiv.org/abs/2606.18583)
  Code: [None](https://)
---
