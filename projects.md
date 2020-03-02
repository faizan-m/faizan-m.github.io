---
layout: page
title: Projects
key:    page-projects
---

### Visualizing a Robot's Perspective in Augmented Reality
#### AIR Lab, May 2018 - August 2018

**Technologies Used: ROS, Unity, C++, C#, Python**

*Motivation:* 
* Internal state of robots is often encoded in a way that is difficult to understand for users 
* Having a fast, high-bandwidth medium to understand them can be valuable for human-robot interaction and robotics education

*Role:*
* Proposed the project for Tufts Summer Scholars and received funding to pursue it
* Designed the overall system architecture and the information pipeline
* Developed ROS Nodes in C++ to transform, sample and compress robot data
* Developed a Unity application to request and parse the data into visualizations
* Developed the visual tracking system using Vuforia and Laser Cutting

*Technical Details:*
* Supports visualizations of robot perception, belief and planning: LIDAR, Costmap, Path Planning, Localization Particles
* Supports Hololens, iPad, Android phones and tablets
* This [report](https://ieeexplore.ieee.org/document/8673191) covers the system architecture in detail

*Results:*
* Conducted a preliminary pilot study investigating use for navigation in shared spaces
* Presented a [Late Breaking Report](https://ieeexplore.ieee.org/document/8673191) in HRI 2019 conference in South Korea
* Part of the Tufts [proposal](https://www.eecs.tufts.edu/~jsinapov/VAR5G/) that won the 2019 [Verizon 5G EdTech Challenge](https://www.5gedtechchallenge.com/)
* Featured in an official Tufts University [video](https://www.youtube.com/watch?v=9_9RNRNd9y8) and an [article](https://now.tufts.edu/articles/hands-research-undergraduates)
* Video below shows a screen-recording as captured from an iPad


<div>{%- include extensions/youtube.html id='WjxJnggaNr8' -%}</div>

---

### Robot Teleoperation through Neuromuscular Control
#### CTRL Labs Internship, May 2019

**Technologies Used: Go, Vincross Hexa**

CTRL Labs was developing an EMG-based, non-invasive neural interface called CTRL Kit with potential applications in AR/VR, Robotics and general Human-Machine Interaction. 

*Motivation:*
* Humans have evolved to have a very fine control over our wrist and hands
* Developing interfaces that can extend this degree of control to robots can be valuable
* Applications include remote teleoperation, learning by demonstration and semi-autonomous operation

*Role:*
* Associate EMG-based readings of muscle movements with a hexapod's appendages
* Developed a mode that mimics finger movements of a human hand in the robot's legs
* Developed a soccer-mode that allows users to teleoperate the robot; navigate and kick its individual legs

*Technical Details:*
* Developed an API in Go programming language for CTRL Kit
* Developed software to parse neuromuscular information to instructions for the robot
* Generate action requests for the robot's body parts concurrently

*Results:*
* The NPR video below shows the hexapod in action as well as introduces the technology behind CTRL Labs
<div>{%- include extensions/youtube.html id='cdZLg4IORc0' -%}</div>

---

### Faster Factoring Algorithms through Quantum Annealing
#### Senior Capstone Project, Sep 2019 - May 2020

**Technologies Used: Quantum Computing, Haskell, Python** 

*Motivation:*
* Semi-prime factorization is an important operation for several reason including cryptography
* Full-scale Quantum Computers do not exist as of today but we can exploit Quantum Annealers to obtain speedups over classical computers

*Role:*
* Design circuits to perform the computations such as GCD and operations using Elliptic Curve Method
* Work with our sponsor at IQC to have those circuits implemented
* Generate problem instances annd benchmark their complexity and algorithm performance

*Technical Details:*
* The speedup was suggested by the following [pre-print](https://arxiv.org/abs/1910.09592)
* Check out our [design doc](/assets/docs/CapstoneDesignDoc.pdf) for more details!

*Results:* 
* So far we have been working on learning relevant material and attempting to draft circuits for the Elliptic Curve Method. 

{% include image-caption.html imageurl="/assets/images/projects/dwave.jpg" title="DWave" caption="" %}

---

### Trinity College International Fire Fighting Robot Contest
#### Tufts Robotics Club, April 2019

**Technologies Used: ROS, C++, Python, Raspberry Pi, Arduino** 

*Motivation:*
* Yearly contest held in Trinity College that simulates a fire-emergency scenario
* Develop a robot system that can be iteratively improved upon in subsequent years

*Role:*
* Led the development of the club's first ROS-enabled robot in 2019
* Manage hardware, electrical and software teams
* Taught ROS to fellow members

*Technical Details:*
* A central Raspberry Pi 3B+ running ROS
* An Arduino Mega facilitating the Pi by interacting with sensors and actuators in real time
* Equipped with LIDAR and a servo controlled fire-extinguisher
* Biggest challenge was tuning the mapping and path-planning algorithms to run on limited computation power

*Results:*
* Capable of point-point navigation in an unknown environment using SLAM
* Club's first functional ROS-powered robot
* Won the Olympiad in Senior Individual Category in [2018](https://tuftsdaily.com/news/2018/04/24/tufts-robotics-wins-international-competition-trinity-college/) and 2019.

{% include image-caption.html imageurl="/assets/images/robotics/trin19.jpg" title="Robot19" caption="" %}

--------

### Sound Based Robot Localization
#### Probabilistic Robotics Class, May 2019

**Technologies Used: MATLAB, Machine Learning** 

*Motivation:*
* Indoor navigation for robots in environments where physical layouts keep changing is difficult
* This difficulty arises due to usage of sensory systems that rely on these physical features (LIDAR, Cameras)
* The acoustic properties of a room are dependent mostly on the shape of the room
* Identifying rooms based on their acoustic properties might help robots find themselves when they are lost

*Role:*
* Designed the proposal for the class project
* Developed software in MATLAB alongside
* Evaluated and presented our results

*Technical Details:*
* Used a Sine Sweep to generate Room Impulse Response (RIR)
* Extracted features from the RIR
* Used SVM on these features to predict room

*Results:*
* The code, datasets and the project report can be found [here](https://github.com/gyawalisaurav/AudioLocalization).
* The confusion matrix below outlines our final cross-validation results based on a dataset collected across 3 spaces with 50 samples each. 
* Class 1 is a small lab room, Class 2 is an open lounge space and Class 3 is a section of a corridor. 
* It works practically perfectly within the dataset in being able to tell the lab room apart from the corridor
* There is some error within the open lounge space. 
* Itmight be due to the possibility that the open lounge does not have a single acoustic profile throughout itself.
* We also tried to predict position in room given which room it is in but did not find any solid results.

{% include image-caption.html imageurl="/assets/images/projects/soundConfusion.PNG" title="sound" caption="" %}


--------

### Clappy Bird
#### Digital Circuits Class, May 2019

**Technologies Used: VHDL, FPGA, Lattice Radiant** 


We recreated the popular game Flappy Bird in an FPGA using claps as the means to control the game (hence the name). We used an Arduino Nano to interface with the microphone and detect claps due to technical difficulties with the ADC but the entire game logic and rendering is done within the FPGA using clocks, flip-flops, latches, multiplexers etc. in VHDL. The video below demonstrates the system in action:
<div>{%- include extensions/youtube.html id='YWPLAgdawzo' -%}</div>
The code and the project report can be found [here](https://github.com/faizan-m/ClappyBird).

--------

### Programming Robots through Paper Worksheets
#### CEEO, August 2017

**Technologies Used: OpenCV, C++, LabVIEW** 


I wrote code to automatically and robustly extract different sections of worksheets based on given scanned images. This would act as a convenient classwork digitization tool which allowed teachers to go through the classwork section by section and share any interesting responses with the class. 

Using that tool, I explored the possibility of digitally parsing some of those sections into meaningful data. As a particular examples, a programmable worksheet was devised and implemented that young students could simply draw on to program robots:

{% include image-caption.html imageurl="/assets/images/experience/worksheet.PNG" title="robotsheet" caption="" %}

--------

### Simple Robotics Projects
#### Intro to Robotics Class, September 2016

**Technologies Used: LabVIEW, Lego Mindstorms** 


Simple Robotics was one of the first classes I took at Tufts. The class focused primarily on the creative design process behind building robots. We had the opportunity to build fun robots every week. Here, for example, is an animatronic Jack Sparrow that yells at you if you take his candy:

<div>{%- include extensions/youtube.html id='r5JbENtdH3c' -%}</div>

And this is me as a sassy, robot-wielding magician: 
<div>{%- include extensions/youtube.html id='MnFt0QF9FBY' -%}</div>


