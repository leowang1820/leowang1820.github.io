---
layout: single
permalink: /research/coordinated-tracking-stability-control/
title: "Coordinated Tracking and Stability Control"
author_profile: true
---

<p class="research-kicker">Research Area 02</p>

<img class="research-hero" src="/images/research/coordinated-control.jpg" alt="Presentation on coordinated tracking and vehicle stability control">

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

- Use a controlled stability region to quantify the available dynamic margin.
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
