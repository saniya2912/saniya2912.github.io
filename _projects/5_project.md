---
layout: page
title: Extremum-Seeking Active Object Recognition in Clutter
description: Summer Research Internship 2023, University of Washington
img: assets/img/locobot.jpeg
importance: 5
category: work
related_publications: true
---

 Object recognition in unseen and cluttered indoor
 scenes is a challenging problem for semantic-level mapping and
 manipulation tasks involving low-cost mobile robots. In this
 project, we propose a novel framework to address this problem
 through active robot navigation. Using this framework, the
 robot performs instance segmentation and identifies the objects
 using a 3D point cloud slicing-based topological descriptor. It
 also optimizes its pose autonomously via an extremum seeking
 controller to improve the identification confidence scores. Re
sults show that our framework always improves the recognition
 success rate for any given scene as the robot moves to better
 pose(s), regardless of the number of objects in the scene, degree
 of clutter, distance to the objects, and lighting condition.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pipeline.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
My contribution in this project was designing a control system to identify and navigate to the next best view of the cluttered scene, employing extremum-seeking control as the optimal solution to maximize the object recognition score. This approach enabled the system to dynamically adjust its viewpoint to enhance recognition accuracy. The control system was successfully integrated into a LoCoBot equipped with an RGBD camera, utilizing the ROS framework to manage the robot's movements and data processing. 
</div>

