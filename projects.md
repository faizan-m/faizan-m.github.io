---
layout: article
title: Projects
key:    page-projects
aside:
  toc: true
---
(This section does not include some research projects which can be found in the [Experience](https://faizan-m.github.io/experience.html) section)

## Trinity College International Fire Fighting Robot Contest
### (Project Management, ROS, C++, Python, Micro-controllers)

I have been involved with the contest since my freshman year of college as part of [my role in the Tufts Robotics Club](/experience.html#co-president-tufts-robotics-club). 

In 2018, I led the development of the software architecture for the robot which was based on a central Raspberry Pi Zero interfaced with an Arduino Mega. 

<div class="hero hero--dark" style='height: 500px; background-image: url("/assets/images/robotics/trin18.jpg");'>
</div>

In 2019, I led the full-stack development of the robot with a focus on having dedicated real time subsystems running on Arduinos and a central Raspberry Pi 3B+ running ROS. It was our first completely self-made robot that was capable of Point-to-Point navigation while doing SLAM (Simultaneous Localization and Mapping) using a LIDAR. Previously, we had been relying on heuristics like Wall-Following for navigation. Apart from hardware design and electronics setup, the key challenge for this robot was building a robust navigation stack which included writing our own controllers for motors as well as tuning mapping and path-planning parameters to the limited processing power of the 3B+.

<div class="hero hero--dark" style='height: 420px; background-image: url("/assets/images/robotics/trin19.jpg");'>
</div>

The contest also organizes an Olympiad every year that focuses on the theoretical aspects of Robotics. I won the Olympiad in Senior Individual Category in 2018 and 2019.

## Sound Based Robot Localization
### (MATLAB, Machine Learning)

We prototyped a potential localization system that could be used to augment navigation abilities of robots in our CS building. We used a Sine Sweep to generate Room Impulse Response (RIR). We then extracted some features from the RIR to predict which area of the building the robot was in using Machine Learning. It relies on the idea that different spaces within the building will have different acoustics and hence these spaces could be potentially identified by them. 

The confusion matrix below outlines our final cross-validation results based on a dataset collected across 3 spaces with 50 samples each. Class 1 is a small lab room, Class 2 is an open lounge space and Class 3 is a section of a corridor. While it works practically perfectly within the dataset in being able to tell the lab room apart from the corridor, there is some error within the open lounge space. We thought that might be due to the possibility that the open lounge does not have a single acoustic profile throughout itself. We tried to exploit that by using RIR to predict position in room given which room it is in but did not find any solid results.

<div class="hero hero--dark" style='height: 600px; background-image: url("/assets/images/projects/soundConfusion.PNG");'>
</div>

The code, datasets and the project report can be found [here](https://github.com/gyawalisaurav/AudioLocalization).

## Clappy Bird
### (Digital Circuits, VHDL, FPGA, Lattice Radiant)

We recreated the popular game Flappy Bird in an FPGA using claps as the means to control the game (hence the name). We used an Arduino Nano to interface with the microphone and detect claps due to technical difficulties with the ADC but the entire game logic and rendering is done within the FPGA using clocks, flip-flops, latches, multiplexers etc. in VHDL. The video below demonstrates the system in action:
<div>{%- include extensions/youtube.html id='YWPLAgdawzo' -%}</div>
The code and the project report can be found [here](https://github.com/faizan-m/ClappyBird).

## ReVRSR
### (C#, Unity, ROS, Oculus Rift)

"Remote Virtual Reality for Service Robots" was my first experience with Unity and using XR as tool for robotics. We developed a simple VR experience that lets the user experience the world from the perspective of a robot that could be located anywhere in the world. This would allow a human user to remotely take over and operate the robot when something goes wrong. The key challenge in this project was interfacing ROS with Unity. 

<div class="hero hero--dark" style='height: 400px; background-image: url("/assets/images/projects/revrsr.PNG");'>
</div>

The code and project report can be found [here](https://github.com/faizan-m/revrsr). 

Insights and experience from this project led to [my Tufts Summer Scholars research](/experience.html#research-assistant-autonomous-intelligent-robotics-lab-tufts-university) in using Augmented Reality as a medium of interaction with an autonomous robot.


## Simple Robotics
### (LabVIEW, Lego Mindstorms, Robot Design)

Simple Robotics was one of the first classes I took at Tufts. The class focused primarily on the creative design process behind building robots. We built simple, fun robots every week. Here, for example, is an animatronic Jack Sparrow that yells at you if you take his candy:
<div>{%- include extensions/youtube.html id='r5JbENtdH3c' -%}</div>

And this is me as a sassy, robot-wielding magician: 
<div>{%- include extensions/youtube.html id='MnFt0QF9FBY' -%}</div>


