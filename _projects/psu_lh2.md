---
layout: page
title: LH2 Transport Aircraft
description: Evaluating LH2 and SAF as alternative fuels for commercial aircraft
img: assets/img/edited_aircraft_family_plan_white_background.svg
importance: 3
category: Penn State
related_publications: true
---

## Motivation

Electrificaiton has been proposed as a techology that could improve rotorcraft performance. While signifcant effort has been devoted to evaluating urban air mobility concepts, this project seeks to explore the potential benefits of hybrid-electric propulsion for larger rotorcraft. 
 
Hybrid-electric propulsion requires integration of electric motors with complex mechanical gearboxes. Understanding where, when, and how to add or remove electric power opens a vast design space that has yet to be explored fully. 

## Approach

This project leverages Geometric Programming using [GPkit](https://gpkit.readthedocs.io/en/latest/) to explore this large design space. Geometric programs (GPs) are convex in log spcae, and can be solved quickly using “off-the-shelf” solvers. The drivetrain, vehicle, and mission performance models are implemented as GPs and solved using a simultaneous analysis and design (SAND) approach. 

Discrete hybrid-electric powertrain topologies are defined by combining gearbox and electric machine models such that the optimizer solves for the gear ratios, speeds, and electric machine torques that maximize mission performance. Using epicyclic gearboxes, electric machines can produce variable output speeds. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/powertrain_2_white_background.svg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/powertrain_2_white_background.svg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, a motor adds power to the main rotor using either a generator or battery in a constant speed configurations. Right, a generator removes and redistributes power from an epicyclic gearbox to vary the rotor speeds. 
</div>

## Results

General conclusions from this work are as follows: 
- Electrification could provide an incremental performance improvement (on the order of 2-5%) for large rotorcraft
- The primary benefit mechanisms are as follows:  
    - using small amounts of electric power with batteries at short duration peak power conditions reduces peak turbine power demand and improves engine efficiency throughout the flight
    - variable rotor speed enables optimization of the blade loading coefficient, $\left( C_T / \sigma \right)$, as the vehicle weight changes. 

The sizing approaches required for realizing these benefits have important implications on the vehicle performance. The magnitude of the benefits ultimately depend on the mission, objectives, and sizing constraints. 


<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/fuel_flow_benefit.svg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/rotor_speed_benefit.svg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left, engine downsizing benefit. Right, vairable rotor speed benefit. 
</div>

For more information, refer to our publications {% cite vanlandingham2023conceptual %} {% cite vanlandingham2024environmental %}. 


