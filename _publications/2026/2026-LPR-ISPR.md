---
title:          'Generative Intermediate-State Prior for Phase Retrieval'
date:           2026-07-17 00:01:00 +0800
selected:       true
pub:            "Laser & Photonics Reviews (IF: 9.7)"
pub_date:       "2026"
abstract: >-
   Phase retrieval aims to recover the complex optical field from intensity measurements and is a fundamental ill-posed problem in computational optical imaging. It propagates measured amplitudes through a physical model to obtain measurement-related intermediate states, then back-propagate them to the target domain for correction. However, existing methods impose regularization only in the target domain, ignoring structural disturbance in the intermediate states that can become coupled with the target-domain estimates during propagation thus hard to remove. To address this issue, an Intermediate-State Prior-based Phase Retrieval framework (ISPR) is proposed, which introduces explicit regularization in the intermediate state. First, a generative diffusion model characterizes the complex data distributions in the intermediate state, suppressing structural disturbance before being propagated to the target domain. Second, a physics-based data-fidelity module is applied in the target domain to enforce measurement consistency and system-specific constraints. Experimental results demonstrate that ISPR consistently improves reconstruction quality and robustness across different computational imaging tasks. In digital holography, it preserves fine edge details, particularly near image boundaries, while in Fourier ptychographic microscopy, it improves convergence and stability. These results indicate that early suppression of structural disturbance in the intermediate state prevents propagation and accumulation, leading to better structural fidelity.
   
cover:          assets/images/covers/ISPR.png
authors:
  - Yaolong Fa
  - Qiao Wan
  - Wenbo Wan
  - Tao Yang
  - Xianghong Zou†
  - Yuhao Wang
  - Qiegen Liu†

links:
  Project: https://xxx
  Papar: https:xxx
  Code: https://xxx
---
