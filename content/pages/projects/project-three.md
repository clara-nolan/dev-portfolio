---
type: ProjectLayout
title: PBR Path Tracer
colors: colors-a
date: '2022-01-22'
client: ''
description: An offline path tracer made using OpenGL and C++
featuredImage:
  type: ImageBlock
  url: /images/image_2024-10-05_233643711.png
  altText: Project thumbnail image
media:
  type: ImageBlock
  url: /images/myCornell.png
  altText: Project image
---
In this project, my primary goal is to implement the Li\_Full Integrator, a new light integrator designed to handle both direct and global illumination at each ray intersection. This development aims to minimize noise and enhance brightness in the rendered images. I have introduced a function to calculate direct lighting using multiple importance sampling, specifically tailored for interactions with diffuse and microfacet surfaces. Additionally, I have generated new BSDF-based rays to explore global illumination effects further and updated the color accumulation based on the materials each ray encounters. To add another layer of realism, especially in scenes devoid of direct light sources, I have enabled sampling from the environment map.

TLDR; a PBR path tracer that handles global illumination, diffuse, specular, and mirror to translucent material.



