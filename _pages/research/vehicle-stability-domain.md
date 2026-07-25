---
layout: single
permalink: /research/vehicle-stability-domain/
title: "Vehicle Lateral Stability Analysis"
author_profile: true
---

<p class="research-kicker">Research Area 01</p>

<img class="research-hero" src="/images/research/stability-domain.jpg" alt="Presentation on multidimensional vehicle stability domains">

## Brief

This research investigates how to characterize the nonlinear stability
of vehicles in multi-factors. The objective is to provide an interpretable and
computationally efficient stability boundary that can be used by planning and
control algorithms under changing driving conditions.

## Motivation

Vehicle stability is fundamental to the safe operation of intelligent vehicles, and the real-time, accurate characterization of the stability domain is crucial for maintaining control across diverse driving conditions. However, the actual stability domain is difficult to parameterize because it is jointly shaped by vehicle dynamics, environmental conditions, time-varying driving inputs, and active control capabilities. Existing methods struggle to capture these multidimensional couplings and often adopt conservative assumptions, thereby underestimating the available stability margin and restricting vehicle performance.
For distributed-drive electric vehicles, independent four-wheel torque control and steering coordination can actively extend the controllable stability region. Nevertheless, existing studies rarely investigate closed-loop stability under such multi-actuator control or systematically exploit the resulting controlled stability characteristics. Consequently, trajectory-tracking controllers generally rely on simplified stability constraints, which may cause unnecessary interventions and degrade tracking performance in extreme scenarios such as high-speed cornering and low-adhesion driving.

## Approach

- Analyze nonlinear lateral dynamics in phase-plane and multidimensional state spaces.
- Construct stability boundaries using physics-based indicators and data-driven mapping.
- Estimate the stability domain online as vehicle states and operating conditions change.
- Integrate the resulting boundary into path-tracking and stability-control frameworks.

## Related publications

1. **Chengye Wang**, Yu Zhang, Xuepeng Hu, Haipeng Qin, Guoli Wang, and Yechen Qin, "[Real-time multidimensional vehicle dynamic stability domain calculation and its application in intelligent vehicles](https://leowang1820.github.io/files/artilce/2025-01-7324.pdf)," SAE International, ICVS 2025.
2. Yu Zhang, **Chengye Wang**, Fu Du, Mingming Dong, Yechen Qin, and Ming Mao, "[Dynamic Region of Stability Integrated Path-tracking Control for Intelligent Vehicles](https://leowang1820.github.io/files/artilce/基于动态稳定边界的智能车辆路径跟踪控制方法_张钰.pdf)," Chinese Journal of Mechanical Engineering, accepted.

<a class="research-back" href="/research/">← Back to all research</a>
