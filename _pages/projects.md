---
layout: archive
title: ""
permalink: /projects/
author_profile: true
---

{% include base_path %}

<!-- {% for post in site.projects reversed %}
  {% include archive-single-project.html %}
{% endfor %} -->
<style type="text/css" rel="stylesheet">
.divider {
  display: flex;
  align-items: center;
  text-align: center;
}

/* To show the lines on right 
and left sides of the text */
.divider::before,
.divider::after {
  content: "";
  border-bottom: 1px solid #fac896;
  flex: 1;
}
/* Space on left and right sides of text */
.divider:not(:empty)::before {
  margin-right: 0.25em;
}

.divider:not(:empty)::after {
  margin-left: 0.25em;
}

.newsblock { 
    background-color: transparent;
    border: 1px solid silver;
    padding: 0.1em 0.3em;
}
</style>

<div class="divider"><div style="color:#787878">RA @ UMass Lowell</div></div>
<div class="newsblock">
  <li><b>Scalable graph processing: BFS acceleration on GPUs.</b>
  <p style="text-align:justify;">Attracted by the enormous potentials of Graphics Processing Units
  (GPUs), an array of efforts has surged to deploy Breadth-First Search
  (BFS) on GPUs, which, however, often exploits the static mechanisms to address the challenges that are dynamic in nature. Such a mismatch prevents us from achieving the optimal performance for
  offloading graph traversal on GPUs. To this end, we propose XBFS framework that leverages the runtime optimizations atop GPUs to cope with the nondeterministic characteristics of BFS providing several novel techniques design.</p>
  </li>
</div>

<!-- <div class="card" style="margin-bottom: 0.6rem">
  <div class="card-body">
    <h4 class="card-title" style="color: rgba(0,0,0,.68)!important">
      Scalable graph processing: BFS acceleration on GPUs.
    </h4>
  </div>
</div> -->