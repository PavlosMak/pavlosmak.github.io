---
permalink: /
title: "Hello there, I am Pavlos!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second-year MSc Computer Science student at TU Delft. My research interests lie in the intersection of computer graphics, deep learning and computer vision. I am particularly interested in the application of deep learning for computer graphics tasks (like [this](https://arxiv.org/abs/2105.12319) or [this](https://research.nvidia.com/publication/2021-06_real-time-neural-radiance-caching-path-tracing)) and in the combination of classical graphics ideas and data-driven computer vision for capturing environments (like [this](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) and [this](https://alexyu.net/plenoxels/)).

Currently, I am working on the joint reconstruction of object appearance, geometry and physics parameters with the mentorship of [Prof. Petr Kellnhofer](https://kellnhofer.xyz/). In the past, I have worked on physically based rendering with [Prof. Elmar Eisemann](https://graphics.tudelft.nl/~eisemann/), intercontinental robotic teleoperation with [Prof. VP](https://www.google.com/search?channel=fs&client=ubuntu&q=vp+tu+delft) and static analysis for software engineering with [Prof. Andy Zaidman](https://azaidman.github.io/).

I enjoy scuba diving and I am certified PADI Rescue Diver. I also love hiking but [there are no mountains in the Netherlands](https://en.wikipedia.org/wiki/Vaalserberg).

# Selected (Research) Projects
Here are some of the projects I have proudly done or participated in.

## Ambient Light Caching via Approximate Photon Mapping
<img src="images/projects/teaser.png" alt="Performance evaluation figures of the ambient light cache.">

Researched and developed a photon mapping-based approach to create
ambient light caches to improve the efficiency of physically based
rendering. [See here for the report.](https://repository.tudelft.nl/islandora/object/uuid:03cc13a5-d0c5-4a45-81fe-f98cd68361a4?collection=education)

## The Unnamed Game Engine
<img src="images/projects/oscillating_dragon.gif" alt="A physically based rendering of the Stanford dragon oscillating between being rusty and having dragon scales.">
OpenGL 3D game engine built with the ENTT entity component
system with support for shadow mapping, physically based materials,
SDF glyph rendering and Bézier curve animations. [Check it out!](https://github.com/PavlosMak/UnnamedGameEngine)

## Visualizing the Gaussian Splatting Optimization
<img src="images/projects/gaussian_optimization.gif" alt="A gif of gaussian kernels moving to fit the appearance and geometry of a train.">

A 3D visualizer that demonstrates how the 3D Gaussian Splatting optimization algorithm adapts the Gaussian Kernels to match the underlying scene's appearance and geometry. Click [here](https://www.youtube.com/watch?v=CgAXgjUcurc) to see it in action and [here](https://github.com/PavlosMak/Gaussians-Optimization-Viewer) for the code.


## Visualizing Practical Path Guiding
<img src="images/projects/practical.png" alt="A visualization of how the spatio-directional adaptive tree from practical path guiding fits a 3D radiance field.">

An interactive visualization of [Practical Path Guiding](https://studios.disneyresearch.com/wp-content/uploads/2019/03/Practical-Path-Guiding-for-Efficient-Light-Transport-Simulation.pdf) by Müller, Gross and Novák. We reimplement their technique in a custom 2D path tracer, reducing the radiance field and the proposed adaptive spatio-directional tree to three dimensions (instead of five). Since the tree and radiance field are 3D we can then visualize how the first adapts to fit the second. 


## Blender Geometry Processing
<img src="images/projects/max.png" alt="Max Planck getting his chin enlraged">

A Blender 3D plugin that implements various geometry processing algorithms. Specifically I worked on implementing and evaluating different [variants of the Iterative Closest Point algorithm](https://ieeexplore.ieee.org/abstract/document/924423) and numerous mesh editing brushes based on Laplacian and gradient transformatoins. See [here for a demo](https://www.youtube.com/watch?v=GvlJ_SaGOhw) and [here for the code](https://github.com/Jorgeromeu/blender-geometry-processing).

## TestKnight
Published in [ICSE 2022](https://dl.acm.org/doi/abs/10.1145/3510454.3517052). An automated tool that assists in software testing engineering. Developed as a plugin for the Intellij Idea, available in the [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/17072-testknight). Code available [here](https://github.com/SERG-Delft/testknight).