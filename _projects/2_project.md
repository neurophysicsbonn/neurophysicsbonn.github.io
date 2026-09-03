---
layout: page
title: Proxy Data for Extreme Events
description: A Dynamics Reservoir Computing Framework
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---

Extreme events — rare, high-impact occurrences such as epileptic seizures, financial crashes, extreme weather phenomena, and infrastructure failures — present a fundamental challenge for scientific modelling: they are inherently rare, difficult to reproduce, and yield only sparse empirical data. This scarcity limits the applicability of conventional statistical and machine learning frameworks that rely on robust sample sizes.
This project develops a novel hybrid methodology combining Ordinal Pattern Transition Networks (OPTNs) and Reservoir Computing (RC) — termed Dynamics Reservoir Computing (DRC) — to generate high-fidelity proxy time series that faithfully replicate the dynamical signatures of transitions into extreme events from limited observations. 
OPTNs provide a model-free symbolic representation of system dynamics, while a dynamics-informed reservoir architecture captures structured temporal dependencies from sparse data. By conditioning the reservoir on topological features extracted via OPTNs, the framework generates proxy sequences that preserve both the statistical and topological signatures of the original extreme event.

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PDEV/front.png" title="header" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    From observing an extreme event in the real world to generating dynamically faithful proxy data.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

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
