---
layout: post
title:  "Particle System - C++"
date : 2019-04-06
excerpt: "A Particle System written in C++, with aims to be as efficient as possible."
project: true
tag:
- portfolio
- games
- programming
- particles
- c++
- particle system
- about
comments: false
---

{% capture images %}
	https://kieranbond.github.io/assets/img/portfolio/particle_system/Smoke.gif
{% endcapture %}
{% include gallery images=images caption="Smoke effect" %}
     
A particle system, written in C++ in an OpenGL framework provided by a lecturer.
	 
This particle system was created for a University assignment, where the main aim is to learn how to create performant code and optimise said code.

{% capture images %}
	https://kieranbond.github.io/assets/img/portfolio/particle_system/BlockParticles.png
{% endcapture %}
{% include gallery images=images caption="Early Particles, before colour and the emitter were added" %}

Whilst I didn't get this Particle system utilising the GPU, I did get to the stages of using a memory pool/'pooling' - which massively increased the performance, likely due to less allocations to memory throughout (instead just doing this in one big chunk). 

Below is some snippets from the repository, mostly looking at the Particle class and the Emitter class. 

{% capture images %}
	https://kieranbond.github.io/assets/img/portfolio/particle_system/EmitterCpp2.png
	https://kieranbond.github.io/assets/img/portfolio/particle_system/ParticleCpp2.png
	https://kieranbond.github.io/assets/img/portfolio/particle_system/ParticleHeader1.png
{% endcapture %}
{% include gallery images=images caption="Code Preview" cols=1 %}


<h2> Resources </h2>

<blockquote class="embedly-card" data-card-controls="0"><h4><a href="https://github.com/KieranBond/Particle-System">KieranBond/Particle-System</a></h4></blockquote>
<script async src="//cdn.embedly.com/widgets/platform.js" charset="UTF-8"></script>
