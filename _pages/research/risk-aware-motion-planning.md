---
layout: single
permalink: /research/risk-aware-motion-planning/
title: "Risk-Aware Decision Making and Motion Planning"
author_profile: true
---

<p class="research-kicker">Research Area 03</p>

<img class="research-hero" src="/images/research/motion-planning.jpg" alt="Vehicle testing on a closed track">

## Brief

This research explores decision-making and motion-planning methods for
autonomous vehicles operating in interactive, uncertain, and dynamically
demanding scenarios. The goal is to generate motion that is not only
collision-free, but also feasible for the vehicle to execute safely.

## Motivation

Planning and vehicle control are often designed separately. Under extreme
conditions, however, a geometrically valid path may demand more tire force or
stability margin than the vehicle can provide. Interactive traffic also
requires the planner to account for uncertainty and the possible responses of
surrounding road users.

## Approach

- Represent interaction risk explicitly during decision making.
- Couple trajectory generation with vehicle-dynamics constraints.
- Consider longitudinal–lateral motion coupling and tire-force limitations.
- Use stability information to reject or reshape dynamically unsafe motion.
- Evaluate the resulting trajectories through simulation and vehicle experiments.

## Related publications

1. Shaoyang Shi, Yu Zhang, Kai Yang, **Chengye Wang**, Zhenfeng Wang, and Yechen Qin, "A Risk-Aware Decision Making and Motion Planning Framework for Interactive Autonomous Driving," ITSC 2026, accepted.
2. Xuepeng Hu, Yu Zhang, **Chengye Wang**, Zhenfeng Wang, and Yechen Qin, "[MCTP: A Multi-Coupled Dynamics Trajectory Planning Scheme for Autonomous Driving in Extreme Conditions](https://leowang1820.github.io/files/artilce/Hu等MCTP.pdf)," IEEE Transactions on Automation Science and Engineering, accepted.

<a class="research-back" href="/research/">← Back to all research</a>
