---
title: "Art Boids"
collection: projects
permalink: /projects/art_boids
excerpt: 'Co-creative system for drawing abstract art using a simulated flock of birds.'
date: 2021-6-16
tags:
  - unity
  - c#
  - art

header:
  overlay_image: /assets/images/art_boids/thumbnail.png
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  teaser: /assets/images/art_boids/thumbnail.png

unity_dir: art-boids-008


citation: 
---

Art Boids is a co-creative system that merges technology, art, and user interaction to create stunning, abstract visuals. The concept revolves around a flock of simulated birds, or "boids," each acting as a unique agent on a digital canvas. Users can customize and interact with these boids, influencing their behavior to generate dynamic and evolving art pieces.

At the heart of Art Boids is Craig Reynolds' "boids" algorithm, which simulates natural flocking behavior. Each boid moves in relation to nearby objects and fellow boids, adjusting its velocity and direction to avoid collisions, maintain separation, and stay aligned with the group. This creates complex, organic movement patterns that users can tweak by modifying parameters such as speed, separation distance, and cohesion force.

As users customize the environment and settings, the boids leave trails on the canvas, creating abstract art in real-time. The system not only lets users observe the flock’s movement, but it also encourages exploration of how different settings interact to produce one-of-a-kind artwork. Whether experimenting with new configurations or refining a specific design, Art Boids offers an immersive creative experience where both the artist and the algorithm work together to generate ever-evolving pieces.

See the demo below.

<!-- ## implementation -->

## Demo

<center>
<!-- unity player -->
{% if page.unity_dir %}
{% include page__unity.html %}
{% endif %}
</center>
 