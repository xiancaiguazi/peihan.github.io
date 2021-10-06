---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My current work is about active visual perception in multi-agent formation control. This work leverages aerial platforms with an active-vision system, i.e., a motorized camera mounted on the drone to have an additional rotational DOF (Degree of Freedom). With this novel hardware, the path planning and visual perception are decoupled as two separate concerns. 

For visual perception, an algorithm is designed to plan to angle of rotation of each camera to meet several requirements: First, each agent should be observed or observe at least one other agent so that the visual perception topology is a connected graph; Second, the rotation of the camera should avoid motion blur of the target agent. The results of visual perception are used for relative localization between agents.

For the path planning, the aerial swarm maintain their formation and avoid collision based on relative localization while performing tasks such area coverage or target following. 

The framework mentioned above is realized in a distributed manner. Agents communicate through UWB network.

[![Agile Formation Control of Drone Flocking Enhanced with Active Vision-based Relative Localization](https://res.cloudinary.com/marcomontalbano/image/upload/v1633524596/video_to_markdown/images/youtube--pyMY54b_c-4-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/pyMY54b_c-4 "Agile Formation Control of Drone Flocking Enhanced with Active Vision-based Relative Localization")

<video src="https://youtu.be/pyMY54b_c-4" controls="controls" width="500" height="300" />
