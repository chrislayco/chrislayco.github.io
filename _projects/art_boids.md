---
title: "art_boids"
collection: projects
permalink: /projects/art_boids
excerpt: 'simulated flock artists'
date: 2021-6-16
tags:
  - unity
  - c#
  - art

header:
  overlay_image: /assets/images/boids_thumbnail.png
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  teaser: /assets/images/boids_thumbnail.png

unity_dir: art-boids-008


citation: 
---

art boids is a co-creative system that allows users to make abstract art using  simulated movement of a flock of birds. Each agent, known as a "boid," acts as a drawer on a canvas that users can interact with and customize to create art. the movements of the boids is based on craig reynolds ``boids" algorithm, which causes each boid to move based on the position of nearly objects and other boids. 

<!-- ## implementation -->

## demo

<center>
<!-- unity player -->
{% if page.unity_dir %}
{% include page__unity.html %}
{% endif %}
</center>
 