---
layout: page
title: Quadruped Robot Stance Stability 
description: Summer Research Internship 2022, IIT Delhi
img: assets/img/quadruped.jpg
importance: 6
category: work
related_publications: false
---

This project presents a novel optimized control strategy for achieving quadruped stability under unforeseen external disturbances. By leveraging Centroidal Dynamics and the Momentum Jacobian Matrix (MJM), the approach uses eigenvalue analysis to optimize control for enhanced stability. A new term, Effective Disturbance Ratio (EDR), is introduced to demonstrate the superiority of the proposed method over existing ones. The control law is tested on a quadruped standing on flat and inclined surfaces, with Center of Mass (CoM) motion analysis showing the effectiveness of the approach.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/result1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Disturbance rejection on flat plane.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/result3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Disturbance rejection on inclined plane.
</div>

