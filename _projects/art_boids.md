---
title: "art_boids"
collection: projects
permalink: /projects/art_boids
excerpt: 'simulated flock artists'
date: 2021-3-27
tags:
  - unity
  - c#
  - art

header:
  overlay_image: /assets/images/boids_thumbnail.png
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  teaser: /assets/images/boids_thumbnail.png

unity_dir: art-boids-007


citation: 
---


art_boids is a casual creative system that utilizes craig reynolds' "boids" algorithm to define the movement for individual boid agents. each boid acts as a drawer on a canvas, that users can interact with and customize to create art.

## implementation

## demo

<center>
<!-- unity player -->
{% if page.unity_dir %}
{% include page__unity.html %}
{% endif %}
</center>
 