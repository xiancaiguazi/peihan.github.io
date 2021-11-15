---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My current work is about active visual perception planning in multi-agent formation control. The vision-based relative localization can provide effective feedback for the cooperation of aerial swarm but was inherently restricted by the limited field of view (FOV) . Inspired by bird flocks in nature, we design an active-vision system, i.e., a motorized camera mounted on the drone to have an additional rotational DOF (Degree of Freedom). 

<div align="center">
 <img src="/images/active-vision-system.gif"  width = "310" height = "240" alt="active-vision system" align="center" />
 &emsp;&emsp;&emsp;&emsp;
 <img src="/images/opt-vision.gif"  width = "240" height = "240" alt="visual perception optimization" align="center" />
</div>


With this novel hardware, we need to consider the planning of visual perception for swarm cooperation. For visual perception, a graph-based attention planning algorithm is designed to plan to angle of rotation of each camera to meet several requirements: First, each agent should be observed or observe at least one other agent so that the visual perception topology is a connected graph; Second, the rotation of the camera should avoid motion blur of the target agent. The results of visual perception are used for relative localization between agents, which is realized in a distributed manner.

Only with proper visual observation graph Laplacian can the formation of the swarm converge. This inforamtion provides guidance for the design of control law and path planning of the swarm.

<!-- For the path planning, the aerial swarm maintain their formation and avoid collision based on relative localization while performing tasks such area coverage or target following.  -->

<!-- The framework mentioned above Agents communicate through UWB network. -->

Research Experiences
======
<div >
 <a href="https://www.youtube.com/watch?v=pyMY54b_c-4" target="_blank">
    <img src="/images/active-vision.png" align = "left" alt="active vision" width="320" height="180" border="10" style="vertical-align:middle"/>
  </a>
 <p> 
   <b>● Agile Formation Control of Aerial Swarm Based on Active Vision</b>
  <br>
   This study proposes a novel active vision framework for multi-robot drone formation which enhances the accuracy of relative localization between agents and demonstrates real-time capabilities of proposed algorithms on real distributed hardware. 
 </p>
</div>
<br /><br />


<div>
 <a href="https://www.youtube.com/watch?v=VPgk_Q9hdwE" target="_blank">
   <img src="/images/ground-aerial.png" align = "left" alt="ground-aerial inspection" width="320" height="180" border="10" style="vertical-align:middle" />
 </a>
 <p> 
   <b>● Ground-Aerial Cooperative Inspection System with Continuable Charging</b>
  <br />
   This study proposes an aerial-ground cooperative architecture that aims to inspect a given area. Unmanned Aerial Vehicles (UAVs) perform the area coverage mission while the Unmanned Ground Vehicle (UGV) serves as an intelligent charging station to prolong the operation time of aerial swarms.
  </p>
</div>
<br /><br />


<div>
 <a href="https://www.youtube.com/watch?v=nDiZuc0lM-s" target="_blank">
   <img src="/images/quayside-inspection.png" align = "left" alt="quayside inspection" width="320" height="180" border="10" style="vertical-align:middle" />
 </a>
 <p> 
   <b>● Autonomous UAV Inspection for Port Machine in Digital Twin</b>
  <br />
   This study develops a simulated port environment with PX4, Gazebo, and ROS, which can import over 20 types of port machines to 100m×100m size inspection scenarios, satisfying the need for a more efficient and safer autonomous aerial inspection of the world's largest port machinery manufacturer.
  </p>
</div>
<br /><br />


Selected Projects
======
<div style="margin:10 width:100%" >
<a href="https://www.youtube.com/watch?v=k0W_9xlVHAk" target="_blank">
   <img src="/images/3D-reconstruction.png" align = "left" alt="quayside inspection" width="320" height="180" border="10" style="vertical-align:middle" />
 </a>
<p> 
   <b>● 2020 Fast 3D Reconstruction of Internal Factory by the Aerial Vehicle </b>
   <br /><br /><br /><br /><br />
</p>
</div>
<br /><br />


<div style="margin:10 width:100%" >
 <a href="https://www.youtube.com/watch?v=wfi7CVHrzNU" target="_blank">
   <img src="/images/drone-competition.png" align = "left" alt="drone-competition" width="320" height="180" border="10" style="vertical-align:middle" />
 </a>
 <p> 
   <b>● 2020 The 4th Intelligent Unmanned Aerial Vehicle Competition </b>
   <br /><br /><br /><br /><br />
  </p>
</div>
<br /><br />

