---
layout: page
title: Powertrain Testbed
description: Emulating full-scale turbomachinery to evaluate predictive energy management control frameworks 
img: assets/img/full_lab.jpg
importance: 2
category: Penn State
related_publications: true
---

## Motivation

Electrification can improve performance for fixed-wing and rotary-wing aircraft propulsion applications. The Penn State Electrified Aircraft Powertrain Testbed was developed to design and test advanced hybrid electric control strategies for fixed-wing and rotary-wing aircraft. The objective was to develop a modular and flexible framework for full-scale control system development, allowing integration of control system design at earlier stages in the design process. 

## Approach

Dynamic emulation using electric machines allows a 3 kW motor-generator pair to mimic the interactions of various shaft power sources and loads including turbomachinery, propulsors, and full-scale motors and generators. 

Simulated models of full-scale components run in real-time on a Speedgoat target machine. The testbed hardware follows the scaled torque and speed references of the real-time models. Each shaft emulator state is fed back as measured states of the full-scale control system. 

The lab currently includes three motor-generator pairs that are coupled in software to emulate various components within the powertrain. In the coming months, we will be expanding to include six total pairs that allow study of advanced hybrid-electric rotorcraft powertrains.

<div class="row justify-content-sm-center align-items-center">
    <div class="col-sm mt-12 mt-md-0">
        {% include video.liquid path="assets/video/motor_demo.mp4" title="motor_speed_demo" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Closed-loop speed control demonstration for three shaft emulators. 
</div>

For more detail on the emulation and scaling approach, please refer to our publications {% cite vanlandingham2025subscale %}. 
