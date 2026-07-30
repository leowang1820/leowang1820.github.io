---
layout: single
permalink: /research/coordinated-tracking-stability-control/
title: "Coordinated Tracking and Stability Control"
author_profile: true
---

<p class="research-kicker">Research Area 02</p>



## Brief

This project studies how an automated vehicle can continue following its
desired path while remaining dynamically stable near the limits of tire
adhesion. The central problem is to coordinate tracking performance and
stability intervention instead of treating them as two unrelated objectives.

## Challenge

Aggressive path-tracking commands can increase lateral tire demand precisely
when the available stability margin is small. A stability controller that
intervenes too late may not recover the vehicle, while an overly conservative
controller can significantly degrade path-tracking performance.

## Approach

- Controlled Stability Region-Guided Lateral-Longitudinal Trajectory Tracking for Autonomous Vehicles.

<div class="youtube-video">
  <iframe
    src="https://youtube.com/shorts/VU_aiadBjVI?feature=share"
    title="Controlled Stability Region-Guided Lateral-Longitudinal Trajectory Tracking for Autonomous Vehicles"
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

- Retain the path-tracking steering demand as the nominal motion command.
- Introduce corrective yaw-moment control when the vehicle approaches its stability boundary.
- Coordinate the two objectives according to the current vehicle state and stability margin.
- Validate the framework in representative limit-handling scenarios.

## Related publication

**Chengye Wang**, Yu Zhang, Xuepeng Hu, Shaoyang Shi, Jingqi He, and Yechen Qin,
"Coordinated Tracking and Stability Control of Automated Vehicles at the
Limits: A Controlled Stability Region Approach," 2026 IEEE 29th International
Conference on Intelligent Transportation Systems (ITSC), accepted.

<a class="research-back" href="/research/">← Back to all research</a>
