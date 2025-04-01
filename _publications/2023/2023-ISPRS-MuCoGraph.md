---
title:          'MuCoGraph: A Multi-scale Constraint Enhanced Pose Graph Framework for MLS Point Cloud Inconsistency Correction'
date:           2023-09-21 00:01:00 +0800
selected:       true
pub:            "ISPRS Journal of Photogrammetry and Remote Sensing (IF: 12.7)"
pub_date:       "2023"
abstract: >-
  The position consistency of mobile laser scanning (MLS) point clouds is crucial for large-scale applications, and is normally guaranteed by the global navigation satellite system (GNSS) and high-precision inertial measurement unit (IMU) in the data acquisition. However, GNSS-denied environments such as city valleys result in significant position inconsistency for overlapping areas, and it is difficult to automatically locate these inconsistent areas. In this paper, to overcome these problems, we present MuCoGraph, which introduces multi-scale constraints to establish the correct correspondences for revisited areas, and formulates an enhanced pose graph for position inconsistency correction. The georeferenced MLS point cloud is first sliced into segments adaptively, and these segments are then abstracted as graph vertices, which satisfy local geometric consistency and rigid transformation hypotheses. Accurate revisited graph edges are then constructed hierarchically under multi-scale scenery consistency constraints. These revisited edges are initialized based on feature-based correspondence estimation and further unreliable edge pruning. Finally, through combination with virtual co-observations, correspondence-enhanced pose-graph optimization is introduced to globally redistribute the errors and obtain a high-precision point cloud. The proposed method was used to correct the MLS point cloud position inconsistency in three datasets. The average three-dimensional distance of the checkpoints was reduced from 0.362 m, 0.108 m, and 1.027 m to 0.057 m, 0.033 m, and 0.051 m for datasets I, II, and III respectively. In addition, the root-mean-square error of all three datasets was less than 0.04 m after correction. The experiments confirmed that the proposed method can automatically locate and correct the position inconsistency of MLS point clouds, showing good robustness and effectiveness.

cover:          assets/images/covers/MuCoGraph.png
authors:
  - Yuhao Li Zou
  - Xianghong Zou
  - Tian Li
  - Sihan Sun
  - Yuan Wang
  - Fuxun Liang
  - Jianping Li†
  - Bisheng Yang†
  - Zhen Dong

links:
  Paper: https://www.sciencedirect.com/science/article/pii/S0924271623002599
---
