---
layout: page
title: Proxy Replica Brain (PRB)
description:  A multilevel multilayer network approach to epileptic brain dynamics
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

The PRB project develops an innovative in silico model for the personalized characterization and prediction of epileptic seizures. 
Its scientific innovation lies in a fundamentally new in silico methodology consisting of three synergistic components:

1. **Directed multilayer networks:** Functional interaction networks capture both connection strength and directional information between brain regions using Ordinal Pattern Transition Networks (OPTNs).

2. **Dynamics-informed reservoir computing:** Integrating brain-specific OPTN structures into reservoir architectures replaces traditional random topologies and reduces the need for hyperparameter optimization.

3. **Clinical translation through FPGA technology:** A real-time FPGA implementation enables operational seizure prediction in a portable technology suitable for clinical settings.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PRB/header.png" title="header" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Conceptual workflow of the Proxy Replica Brain project, linking directed multilayer brain networks, dynamics-informed reservoir computing, and FPGA-based real-time seizure prediction.
</div>

The extensive EEG database of the Department of Epileptology at University Hospital Bonn enables retrospective validation of this innovative approach and supports the efficient development of an FPGA prototype for clinical studies. 

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
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

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
