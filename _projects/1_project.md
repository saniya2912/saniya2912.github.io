---
layout: page
title: Multi-object Grasping with LEAP Hand
description: Sabarmati Bridge Fellowship, IIT Gandhinagar
img: assets/img/multiobj_1.PNG
importance: 1
category: work
related_publications: true
---

Developing a dynamic sequential grasping strategy for the robotic LEAP hand, utilizing pinch and power grasps, enabling object
transfer between these grasps, and determining the optimal order for picking the objects. 
<!-- 
    <!-- ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- --> -->

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pinch.JPEG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/power.JPEG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/multiobj_1.PNG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Despite an extensive body of work on robot grasping, there are numerous routine human grasping skills that are still out of grasp of robots. One such common skill employed by humans is multi-object sequential picking up and grasping. For instance, humans use a combination of pinch grasp with the thumb and forefinger and a power grasp with the palm and remaining fingers to pick up multiple objects.
<!-- </div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div> -->


<!-- 
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div> -->

<!-- The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above: -->

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
