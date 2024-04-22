---
date: 2024-04-22 13:22:02
layout: post
title: "Game Engine - Intro"
subtitle:
description:
image: /Resources/Images/Posts/GameEngineIntro.png
optimized_image:
category: game engine
tags:
    - game engine
author:
paginate: false
---

*3D Model Rendering with PCSS enabled*

## Introduction

Hello, this is my first blog about my game engine - **Merak**. I built its basic structure during taking the course _EECS 498: Game Engine Arch_ at University of Michigan, and later added more features to it (most focused on 3D rendering). The engine is currently in development.

Here are some interesting features that I have already implemented:

- Lua scripting: Game developers can make games by writing lua scripts
- 3D rendering: The engine uses **Vulkan** as rendering backend, supporting texture mapping, soft shadows, etc.

## Technologies

Here is a brief list of some technologies that I used when developing Merak:

- C++20
- Lua and Luabridge
- Vulkan
- glfw and glm
- Box2D (no longer used in the 3D world)
- 3D Graphics and Real-time Rendering Algorithms

## Demonstration

<p>Short Video Demonstration for the engine:</p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/WQS9LbD62rA?si=zvfFasqhKfNqRnve" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Github Repo

Link to the Github Repo: <a href="https://github.com/AnemoCider/MerakEngine">Github - Merak Engine</a>