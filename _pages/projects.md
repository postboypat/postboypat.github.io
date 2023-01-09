---
layout: default
title: Projects
permalink: /projects/
comments: false
image: assets/images/pg_opengraph_thumb.jpg
imageshadow: true
puiblished: true
---



<div class="row frontpage__intro mb-5">
  <div class="col-md-8 frontpage__intro-bio">
    <h1 class="sitetag-large" style="font-weight:500; font-family: campaign; font-size: 40px;">
      Work.
    </h1>
    <p class="sitetag">
      A selection of my recent projects.
      </p>
  </div>
</div>

<!-- Filter -->
<div class="filter-buttons d-none">
<a data-target="all" class="active" href="#">All</a> ·
<a data-target="motiondesign" href="#">Motion Design</a> ·
<a data-target="branding" href="#">Graphic / Branding</a> ·
<a data-target="mogrts" href="#">Web Design</a>
</div>

<!-- Showreel -->
{% include showreel-modal.html %}


<!-- Projects: Media Card -->
<div class="row project-listing">
  {% assign projects = site.projects | sort: 'date' | reverse %}
  {% for project in projects %}
       {% include project-mediacard.html %}
  {% endfor %}
</div>

<!-- End projects -->
