---
layout: page
title: Projects
key:    page-projects
---

<table>

<thead>
<tr>
   <th>Project Name</th>
   <th>Technologies</th>
   <th>Affiliation</th>
   <th>Date</th>
  </tr>
</thead>

 <tbody>
  <tr>
   <td><a href="/projects#novelty-oriented-ai-agent---darpa-sail-on-project">Novelty Oriented AI Agent - DARPA SAIL-ON Project</a></td>
   <td> Symbolic Reasoning & Planning, RL, Java</td>
   <td> AIR Lab + HRI Lab @ Tufts </td>
   <td> Jan 2020 - May 2020 </td>
  </tr>

  <tr>
   <td><a href="/projects#visualizing-a-robots-perspective-in-augmented-reality">Visualizing a Robot's Perspective in Augmented Reality</a></td>
   <td> ROS, Unity, C++, C#, Python </td>
   <td> AIR Lab @ Tufts </td>
   <td> May 2018 - May 2019 </td>
  </tr>

  <tr>
   <td><a href="/projects#robot-teleoperation-through-neuromuscular-control">Robot Teleoperation through Neuromuscular Control</a></td>
   <td> Go, Vincross Hexa, Docker</td>
   <td> CTRL Labs </td>
   <td> May 2019 </td>
  </tr>

   <tr>
   <td><a href="/projects#trinity-college-international-fire-fighting-robot-contest">Trinity College International Fire Fighting Robot Contest</a></td>
   <td> ROS, C++, Python, Raspberry Pi, Arduino</td>
   <td> Tufts Robotics Club </td>
   <td> Sep 2018 - April 2019 </td>
  </tr>

   <tr>
   <td><a href="/projects#sound-based-robot-localization">Sound Based Robot Localization</a></td>
   <td> MATLAB, Machine Learning</td>
   <td> Probabilistic Robotics Class </td>
   <td> May 2019 </td>
  </tr>

   <tr>
   <td><a href="/projects#clappy-bird">Clappy Bird</a></td>
   <td> VHDL, FPGA, Lattice Radiant</td>
   <td> Digital Circuits Class </td>
   <td> May 2019 </td>
  </tr>

   <tr>
   <td><a href="/projects#programming-robots-through-paper-worksheets">Programming Robots through Paper Worksheets</a></td>
   <td> OpenCV, C++, LabVIEW</td>
   <td> Center for Engineering Education and Outreach </td>
   <td> June 2017 - August 2017 </td>
  </tr>

 </tbody>
</table>


---

### Novelty Oriented AI Agent - DARPA SAIL-ON Project
#### AIR Lab + HRI Lab @ Tufts, Jan 2020 - May 2020

**Technologies Used: Symbolic Reasoning & Planning, RL, Java** 

*Motivation:*
* The [SAIL-ON program](https://www.darpa.mil/program/science-of-artificial-intelligence-and-learning-for-open-world-novelty) was created by DARPA 
* Develop AI that can recognize, handle and adapt to novel environmental changes
* Shift focus beyond limited and controlled domains to more "open-world" ones
* Polycraft (a Minecraft mod) was chosen as one of such environments

*Role:*
* Designed and developed software pipelines to parse sensory information, execute actions, generate facts, plan and learn
* Created the Novelty Detection capabilities of the agent to not only recognize environmental changes but also express them symbolically
* Currently finalizing a paper outlining the system design which is to be published soon

*Technical Details:*
* To be published soon

*Results:* 
* Unseen evaluations by an independent team found it performed better than all other approaches and delivered near-perfect results
* More to be published soon

{% include image-caption.html imageurl="/assets/images/projects/polycraft.png" title="Polycraft" caption="" %}

---
### Visualizing a Robot's Perspective in Augmented Reality
#### AIR Lab @ Tufts, May 2018 - May 2019

**Technologies Used: ROS, Unity, C++, C#, Python**

*Motivation:* 
* Internal state of robots is often highly esoteric
* Develop a fast, high-bandwidth and accessible medium to convey it
* Valuable for human-robot interaction and robotics education

*Role:*
* Proposed the project for Tufts Summer Scholars and received funding to pursue it
* Designed the overall system architecture and the information pipeline
* Developed ROS Nodes in C++ to transform, sample and compress robot data
* Developed a Unity application to request and parse the data into visualizations
* Developed the visual tracking system using Vuforia SDK and Laser Cutting

*Technical Details:*
* Supports visualizations of robot perception, belief and planning
* Specific types include LIDAR, Costmap, Path Planning, Localization Particles
* Supports Hololens, iPad, Android phones and tablets

*Results:*
* Presented a [Late Breaking Report](/publications#creating-a-shared-reality-with-robots) in HRI 2019 conference in South Korea
* Part of the Tufts [entry](https://www.eecs.tufts.edu/~jsinapov/VAR5G/)that won [Verizon 5G EdTech Challenge](https://venturebeat.com/2019/02/07/verizon-reveals-5g-education-tech-winners-hints-at-next-5g-cities/) and the $100K prize
* Featured in an official Tufts University [video](https://www.youtube.com/watch?v=9_9RNRNd9y8) and an [article](https://now.tufts.edu/articles/hands-research-undergraduates)
* Video below shows a screen-recording as captured from an iPad


<div>{%- include extensions/youtube.html id='WjxJnggaNr8' -%}</div>

---

### Robot Teleoperation through Neuromuscular Control
#### CTRL Labs, May 2019

**Technologies Used: Go, Vincross Hexa, Docker**

*Motivation:*
* Humans have evolved to have a very fine control over our wrist and hands
* Interfaces that can extend this degree of control to robots can be valuable
* Remote teleoperation, learning by demonstration and semi-autonomous operation

*Role:*
* Mapped EMG-based readings of muscle activations to hexapod's appendages
* Developed capability to mimic finger movements of a human hand
* Developed capabiltity to kick individual legs and navigate for soccer
* Helped filming of the demo to NPR for their CTRL Labs documentary

*Technical Details:*
* Developed an API in Go programming language for CTRL Kit
* Developed logic to parse neuromuscular information into motor commands
* Generated action requests for the robot's body parts concurrently

*Results:*
* The NPR video below introduces the technology and shows the hexapod in action
<div>{%- include extensions/youtube.html id='cdZLg4IORc0' -%}</div>

---

### Trinity College International Fire Fighting Robot Contest
#### Tufts Robotics Club, Sep 2018 - April 2019

**Technologies Used: ROS, C++, Python, Raspberry Pi, Arduino** 

*Motivation:*
* Yearly contest held in Trinity College that simulates a fire-emergency scenario
* Develop a robot design that can be iteratively improved upon in subsequent years

*Role:*
* Led the development of the club's first ROS-enabled robot in 2019
* Managed hardware, electrical and software teams
* Taught ROS to fellow members

*Technical Details:*
* A central Raspberry Pi 3B+ running ROS
* An Arduino Mega interacting with sensors and actuators in real time
* Equipped with LIDAR and a servo controlled fire-extinguisher
* Biggest challenges:
  * Limited computation power of the Pi
  * Tuning the mapping and path-planning algorithms
  * Developing a robust navigation stack

*Results:*
* Capable of point-point navigation in an unknown environment using SLAM
* Club's first functional ROS-powered robot
* Won the Olympiad in Senior Individual Category in 2018 and 2019

{% include image-caption.html imageurl="/assets/images/robotics/trin19.jpg" title="Robot19" caption="" %}

--------

### Sound Based Robot Localization
#### Probabilistic Robotics Class, May 2019

**Technologies Used: MATLAB, Machine Learning** 

*Motivation:*
* Indoor navigation for robots in changing physical spaces is difficult
* Most common sensors rely on these physical features (LIDARs, Cameras)
* Acoustic properties of a room are dependent mostly on the shape of the room
* Identifying rooms based on their acoustic properties could be helpful

*Role:*
* Designed the proposal for the class project
* Developed software in MATLAB alongside a teammate
* Evaluated and presented our results

*Technical Details:*
* Used a Sine Sweep to generate Room Impulse Response (RIR)
* Extracted features from the RIR
* Used SVM on these features to predict the room

*Results:*
* The code, datasets and the project report can be found [here](https://github.com/gyawalisaurav/AudioLocalization)
* Dataset was collected across 3 spaces with 50 samples each
* Confusion matrix below outlines our final cross-validation results
  * Class 1 is a small lab room
  * Class 2 is an open lounge space
  * Class 3 is a section of a corridor
* Works practically perfectly between the lab room and the corridor
* Some error in the open lounge space possibly because it lacked a consistent profile
* Predicting position in the room given room information did not yield solid results

{% include image-caption.html imageurl="/assets/images/projects/soundConfusion.PNG" title="sound" caption="" %}


--------

### Clappy Bird
#### Digital Circuits Class, May 2019

**Technologies Used: VHDL, FPGA, Lattice Radiant** 

*Motivation:*
* Create an interactive experience for an exposition at the end of class

*Role:*
* Developed digital circuits in VHDL and Lattice Radiant
* Wrote Arduino Code to parse microphone signal

*Technical Details:*
* Recreated the popular game Flappy Bird in an FPGA using claps as the means to control the game (hence the name)
* Used an Arduino Nano to interface with the microphone and detect claps
* Entire game logic and rendering is done within the FPGA using clocks, flip-flops, latches, multiplexers etc. in VHDL

*Results:*
* The code and the project report can be found [here](https://github.com/faizan-m/ClappyBird)
* The video below demonstrates the system in action:
<div>{%- include extensions/youtube.html id='YWPLAgdawzo' -%}</div>

--------

### Programming Robots through Paper Worksheets
#### Center for Engineering Education and Outreach, June 2017 - August 2017

**Technologies Used: OpenCV, C++, LabVIEW** 

*Motivation:*
* Center aims to develop technologies that enhance engineering learning
* [InterLACE](https://ceeo.tufts.edu/research/projectsInterLACE.htm) is a digital tool to help teachers digitize classroom workflow
* Extend InterLACE to automatically extract and organize worksheet subsections

*Role:*
* Developed software in C++ using Visual Studio

*Technical Details:*
* Devised a worksheet template format to specify subsections
* Used OpenCV to detect the sections in a scanned image using the template
* Made the subsection information available for further processing

*Results:*
* Implemented a programmable worksheet as a demonstration
* Young students could simply draw on the worksheet to program a LEGO robot

{% include image-caption.html imageurl="/assets/images/experience/worksheet.PNG" title="robotsheet" caption="" %}


---


