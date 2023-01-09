---
date: 2021-12-01
layout: project
title:  "Experiments"
author: sal
categories: [ Motion Design ]
image: assets/images/experiments/experiments_thumb1.jpg
weight: 10
color1: 79415e
color2: 5a2f46
alt_color: ececec
imageshadow: true
no_feature_image: true
published: false
experiments:
  - name: The Adventures of Clayton
    image: assets/images/experiments/clayton.png
    embedsrc: https://www.youtube-nocookie.com/embed/0gmuFoU0Fn8
    ratio: 1by1
  - name: Jumping Into the Unknown
    image: assets/images/experiments/diver.png
    embedsrc: test
    ratio: 16by9
  - name: Honey Calling
    image: assets/images/experiments/honeycalling.png
    embedsrc: assets/images/experiments/Phone_Render05.mp4
    ratio: 1by1
  - name: Yaho!
    image: assets/images/experiments/yaho-can.png
    embedsrc: https://www.instagram.com/p/embed
    ratio: instagram
  - name: Joysticks and Sliders
    image: assets/images/experiments/joysticks_sliders.jpg
    embedsrc: https://player.vimeo.com/video/494800257?loop=1
    ratio: 1by1
---

<p>This is a space for me to try out new techniques and styles without a particular goal in mind, other than having fun and seeing what comes out of it.</p>

<p>Click on an image to see it in action.</p>

<div class="experiment-grid-container extended">
  {% for experiment in page.experiments %}
    {% include experiment-box.html %}
  {% endfor %}
</div>
