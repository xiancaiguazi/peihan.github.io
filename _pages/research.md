---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My current work is about active visual perception in multi-agent formation control. This work leverages aerial platforms with an active-vision system, i.e., a motorized camera mounted on the drone to have an additional rotational DOF (Degree of Freedom). With this novel hardware, the path planning and visual perception are decoupled as two separate concerns. 

 <img src="/images/active-vision-system.gif"  width = "310" height = "240" alt="active-vision system" align=center />
 &emsp;&emsp;
 <img src="/images/opt-vision.gif"  width = "240" height = "240" alt="visual perception optimization" align=center />


For visual perception, an algorithm is designed to plan to angle of rotation of each camera to meet several requirements: First, each agent should be observed or observe at least one other agent so that the visual perception topology is a connected graph; Second, the rotation of the camera should avoid motion blur of the target agent. The results of visual perception are used for relative localization between agents.

For the path planning, the aerial swarm maintain their formation and avoid collision based on relative localization while performing tasks such area coverage or target following. 

The framework mentioned above is realized in a distributed manner. Agents communicate through UWB network.

Research Experiences
======

<li>
 <a href="https://www.youtube.com/watch?v=pyMY54b_c-4" target="_blank">
   <img src="/images/active-vision.png" align = "left" alt="active vision" width="320" height="180" border="10" />
 </a>
 <div>
  <p> This study proposes a novel active vision framework for multi-robot drone formation which enhances the accuracy of relative localization between agents and demonstrates real-time capabilities of proposed algorithms on real distributed hardware. 
  </p>
 </div>
</li>
<br /><br /><br />


<li>
 <a href="https://www.youtube.com/watch?v=VPgk_Q9hdwE" target="_blank">
   <img src="/images/ground-aerial.png" align = "left" alt="ground-aerial inspection" width="320" height="180" border="10" />
 </a>
 <div>
  <p> This study proposes an aerial-ground cooperative architecture that aims to inspect a given area. Unmanned Aerial Vehicles (UAVs) perform the area coverage mission while the Unmanned Ground Vehicle (UGV) serves as an intelligent charging station to prolong the operation time of aerial swarms.
  </p>
 </div>
</li>
<br /><br /><br />

<li>
 <a href="https://www.youtube.com/watch?v=nDiZuc0lM-s" target="_blank">
   <img src="/images/quayside-inspection.png" align = "left" alt="quayside inspection" width="320" height="180" border="10" />
 </a>
 <div>
  <p> This study	developes an simulated port environment with PX4, Gazebo, and ROS which is able to import over 20 types of port machine to 100m×100m size inspection scenarios, which satisfies the need for more efficient and safer autonomous aerial inspection of the world's largest port machinery manufacturer.
  </p>
 </div>
</li>
<br /><br /><br />

<!-- markdown 插入图片并且给图片附上链接的格式
[![IMAGE ALT TEXT](http://img.youtube.com/vi/GzdKMVn8avo/0.jpg)](https://www.youtube.com/embed/GzdKMVn8avo "CameraMaster") -->

<!-- 不成功的视频插入
<video src="https://www.youtube.com/watch?v=pyMY54b_c-4" controls="controls" width="500" height="300">video not support! </video> -->

Selected Projects
======
<li>
 <a href="https://www.youtube.com/watch?v=k0W_9xlVHAk" target="_blank">
   <img src="/images/3D-reconstruction.png" align = "left" alt="quayside inspection" width="320" height="180" border="10" />
 </a>
 <div>
  <p> 
   <b>2020 Fast 3D Reconstruction of Interal Factory by the Aerial Vehicle </b>
   <br /><br /><br />
  </p>
 </div>
</li>
<br /><br /><br />


<li>
 <a href="https://www.youtube.com/watch?v=wfi7CVHrzNU" target="_blank">
   <img src="/images/drone-competition.png" align = "left" alt="drone-competition" width="320" height="180" border="10" />
 </a>
 <div>
  <p> 
   <b>2020 The 4th Intelligent Unmanned Aerial Vehicle Competition </b>
   <br /><br /><br />
  </p>
 </div>
</li>


