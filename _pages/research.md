---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My current work is about active visual perception in multi-agent formation control. This work leverages aerial platforms with an active-vision system, i.e., a motorized camera mounted on the drone to have an additional rotational DOF (Degree of Freedom). With this novel hardware, the path planning and visual perception are decoupled as two separate concerns. 

 <img src="/images/active-vision-system.gif" width = "425" height = "330" alt="active-vision system" align=center />
 <img src="/images/opt-vision.gif" width = "330" height = "330" alt="visual perception optimization" align=center />


For visual perception, an algorithm is designed to plan to angle of rotation of each camera to meet several requirements: First, each agent should be observed or observe at least one other agent so that the visual perception topology is a connected graph; Second, the rotation of the camera should avoid motion blur of the target agent. The results of visual perception are used for relative localization between agents.

For the path planning, the aerial swarm maintain their formation and avoid collision based on relative localization while performing tasks such area coverage or target following. 

The framework mentioned above is realized in a distributed manner. Agents communicate through UWB network.

Research Experiences
======
* This study proposes a novel active vision framework for multi-robot drone formation which enhances the accuracy of relative localization between agents and demonstrates real-time capabilities of proposed algorithms on real distributed hardware.
<a href="https://www.youtube.com/watch?v=pyMY54b_c-4" target="_blank">
  <img src="/images/active-vision.png" align = "right" alt="active vision" width="320" height="180" border="10" />
</a>
<br>


<!-- markdown 插入图片并且给图片附上链接的格式
[![IMAGE ALT TEXT](http://img.youtube.com/vi/GzdKMVn8avo/0.jpg)](https://www.youtube.com/embed/GzdKMVn8avo "CameraMaster") -->

<!-- 不成功的视频插入
<video src="https://www.youtube.com/watch?v=pyMY54b_c-4" controls="controls" width="500" height="300">video not support! </video> -->

Selected Projects
======
