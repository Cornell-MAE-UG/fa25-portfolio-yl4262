---
layout: project
title: 2D Linear Actuator and Bar Design
description: Statics and Mechanics of Materials
technologies: []
image: /assets/images/hw-4-portfolio.jpg
---
<p></p>

## Purpose
Statics and Mechanics of Materials Project

## Design Challenge
Given a 2D design space of 150cm long and 50cm tall, rigid bar of a fixed length, 3 pin supports of which two need to be mounted on the ground and a linear actuator. We were challenged to find the configuration to lift the maximum possible weight to the highest possible height.

## Approach
With the design restraints, I decided to attach the beam and the actuator so that the actuator and beam would both be pinned to the groud with one pin. The beam and the actuator would be pinned together with the third pin. In order for the weight to be lifted to the highest height, I arranged the beam and actuator in a triangular shape, pinned at the corners of my design space and the weight brought to the top of the design space. I conducted a static analysis of the linear actuator and beam design by looking at the forces exerted on the beam and actuator seperately. 

My unknowns were B, the max value of the force the linear actuator could exert on the beam, W, the weight of the mass lifted by the configuration x, the length of the linear actuator projected in the x-direction, and the reaction forces by the pins. Using a moment calculation, I was able to find the expression for W in terms of B and x, values that was determined by my choice of linear actuator. In order to maximize W, I would need to maximize B, so I picked hte FSX: high force rod-style actuator with a mximum force of 294kN, which is B, and 150cm length. Since the design limits the height of my design, I found with trignometry that x would be 141.4cm. Given width of my design space was 150cm, I found that the length of my beam shoudl be 50.73cm. 

<img src="/assets/images/approach.jpeg" alt="Approach diagram" class="section-image">

I found that the max weight that can be displaced is 97kN at a height of 50 cm. 
