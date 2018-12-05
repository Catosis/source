---
title: "Robots That Know Each Other"
date: 2018-11-20T02:34:57-08:00
draft: false
---
Humans are social creatures. Robots could be too.
-----------
Robotics are often conceptualized to fulfill a specific purpose. They are programmed to assemble a car, traverse rough terrain, or suture a wound. These specialized robots are useful, of course, but each requires significant resources to build, design, and develop and often have a physical shape that would prevent it from specializing in other tasks. 
Swarm robotics are the exact opposite. A swarm is made out of relatively simple objects that can communicate in order to accomplish larger tasks. It takes after the coordination of ants, where the loss of one doesn't impact the others unduly. With enough mass and computing power, a swarm of robots that could  create a mechanical biomass, distributing themselves in complex ways. We see this in nature in the coordinated nature of ants. Tiny bots able work together and build something many times larger than themselves, not unlike how humans work. The potential is endless.
<figure> <center>
<iframe src="https://giphy.com/embed/a9EJq6MtJx5YY" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><figcaption> <font size ="1"> <i>A group of ants collaborating to move something much larger than an individual</font></figcaption></i>
</figure> </center>

When we set out to do this project, we wanted to take a first step in that direction.
If it sounds like science fiction, it's because at this point it mostly is. It's an incredibly complex controls, sensing, and machine learning problem but one that if solved, could open completely new doors for what robots can do. For example, we can see the <a href="http://shape.stanford.edu/research/swarm/" target="blank">Zooids from the Stanfrod SHAPE lab bringing their creator his phone.</a> <a href="https://www.youtube.com/watch?v=ep2-W1X65KI" target="blank">We see a nanobot future in the children's movie Big Hero 6</a>. 

This project is more grounded, intended to be completed in eight months by five mechanical engineers and as a result is a much smaller scope. For our project we wanted motion-controlled robots that were aware of the other robots in the ring, and able to move around with them. They are watched over by a camera that tracks their movements and position, which reports to a desktop computer. The computer calculates the path of each robot such that they do not touch while moving, and sends the commands over wifi on a local network to the robots. Each robot is euipped with a Raspberry Pi Zero with custom motor controllers which recieve only velocity vectors from the central "brain". Having the computation on a large computer speeds up computation a lot, and allows each robot to be an extension of a central mind.
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/8CeJyi4c7eM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 
<figure> 
<img src= "/Robotics/render.jpg" height = 150px><img src= "/Robotics/arena.jpg" height = 150px><img src= "/Robotics/opencv.png" height = 150px>
<figcaption> <font size ="1"> <i>1. A render of our individual robot         2. our arena			3. what the overhead camera sees</font></figcaption></i>
</figure> </center>

