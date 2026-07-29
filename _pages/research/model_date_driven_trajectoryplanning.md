---
layout: single
permalink: /research/model_date_driven_trajectoryplanning/
redirect_from:
  - /research/risk-aware-motion-planning/
title: "Model–Data-Driven Trajectory Planning"
author_profile: true
---

<p class="research-kicker">Research Area 03</p>

## Brief

This research explores trajectory planning method for
autonomous vehicles operating in interactive, uncertain, and dynamically
demanding scenarios. The goal is to generate trajectory that is not only
collision-free, but also dynamically feasible for the vehicle to execute safely.

## Motivation

Under extreme conditions, a dynamically infeasible trajectories may result in vehicle instability, or even accidents under extreme conditions, 
making model-based prediction and constraint enforcement essential 
for ensuring dynamic feasibility and safety. Meanwhile, interactive traffic involves uncertain and context-dependent 
responses that are difficult to represent using handcrafted models alone, motivating data-driven learning to acquire 
adaptive interaction strategies from experience. Therefore, an effective planner should integrate model-based optimization 
for physics-consistent motion generation with data-driven decision-making for complex and uncertain interactions.

## Approach

- Multi-coupled dynamics trajectory planning scheme for autonomous driving in extreme conditions and Real-vehicle test cooperated with BYD.
<div class="youtube-video">
  <iframe
    src="https://www.youtube.com/embed/348yDlYR0g0"
    title="MCTP: A Multi-Coupled Dynamics Trajectory Planning Scheme for Autonomous Driving in Extreme Conditions"
    loading="lazy"
    referrerpolicy="strict-origin-when-cross-origin"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
</div>

<style>
.youtube-video {
  position: relative;
  width: 100%;
  max-width: 700px;
  margin: 1.5rem auto;
  aspect-ratio: 16 / 9;
  overflow: hidden;
  background-color: #000;
  border-radius: 8px;
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.18);
}

.youtube-video iframe {
  display: block;
  width: 100%;
  height: 100%;
  border: 0;
}
</style>

<p>
  If the embedded video cannot be played,
  <a
    href="https://www.youtube.com/watch?v=348yDlYR0g0"
    target="_blank"
    rel="noopener noreferrer">
    watch it directly on YouTube →
  </a>
</p>

- Risk-Aware Decision Making and Motion Planning Framework for Interactive Autonomous  Driving.


## Related publications

1. Shaoyang Shi, Yu Zhang, Kai Yang, **Chengye Wang**, Zhenfeng Wang, and Yechen Qin, "A Risk-Aware Decision Making and Motion Planning Framework for Interactive Autonomous Driving," ITSC 2026, accepted.
2. Xuepeng Hu, Yu Zhang, **Chengye Wang**, Zhenfeng Wang, and Yechen Qin, "[MCTP: A Multi-Coupled Dynamics Trajectory Planning Scheme for Autonomous Driving in Extreme Conditions](https://leowang1820.github.io/files/artilce/Hu等MCTP.pdf)," IEEE Transactions on Automation Science and Engineering, accepted.

<a class="research-back" href="/research/">← Back to all research</a>
