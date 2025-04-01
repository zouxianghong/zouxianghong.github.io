---
title:          'Reliable-loc: Robust sequential LiDAR global localization in large-scale street scenes based on verifiable cues'
date:           2025-03-31 00:01:00 +0800
selected:       true
pub:            "ISPRS Journal of Photogrammetry and Remote Sensing (IF: 12.7)"
pub_date:       "2025"
abstract: >-
   Wearable laser scanning (WLS) system has the advantages of flexibility and portability. It can be used for determining the user's path within a prior map, which is a huge demand for applications in pedestrian navigation, collaborative mapping, augmented reality, and emergency rescue. However, existing LiDAR-based global localization methods suffer from insufficient robustness, especially in complex large-scale outdoor scenes with insufficient features and incomplete coverage of the prior map. To address such challenges, we propose LiDAR-based reliable global localization (Reliable-loc) exploiting the verifiable cues in the sequential LiDAR data. First, we propose a Monte Carlo Localization (MCL) based on spatially verifiable cues, utilizing the rich information embedded in local features to adjust the particles' weights hence avoiding the particles converging to erroneous regions. Second, we propose a localization status monitoring mechanism guided by the sequential pose uncertainties and adaptively switching the localization mode using the temporal verifiable cues to avoid the crash of the localization system. To validate the proposed Reliable-loc, comprehensive experiments have been conducted on a large-scale heterogeneous point cloud dataset consisting of high-precision vehicle-mounted mobile laser scanning (MLS) point clouds and helmet-mounted WLS point clouds, which cover various street scenes with a length of over 30 km. The experimental results indicate that Reliable-loc exhibits high robustness, accuracy, and efficiency in large-scale, complex street scenes, with a position accuracy of ±2.91 m, yaw accuracy of ±3.74 degrees, and achieves real-time performance.

cover:          assets/images/covers/Reliable-loc.gif
authors:
  - Xianghong Zou
  - Jianping Li†
  - Weitong Wu
  - Fuxun Liang
  - Bisheng Yang†
  - Zhen Dong

links:
  Project: https://zouxianghong.github.io/Reliable-loc
  Papar: https://arxiv.org/abs/2411.07815
  Code: https://github.com/zouxianghong/Reliable-loc
---
