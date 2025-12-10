---
layout: page
title: Dynamic Propeller Testing
description: Low-cost out-of-wind-tunnel testing for RC aircraft 
img: assets/img/car_iso_cropped.jpg
importance: 1
category: USC
related_publications: true
---

This was my senior design project at USC completed with [Jacob Iuele](https://www.linkedin.com/in/jacobiuele/) and [Addison Salzman](https://www.linkedin.com/in/addisonsalzman/) {% cite vanlandingham2016out %}. 

## Motivation

Propeller performance varies as a function of airspeed. Ground testing with a thrust stand provides useful information about takeoff conditions, but little about cruise performance. Wind-tunnel testing requires large facilities that are prohibitively expensive for RC aircraft testing.

The goal of this project was to design and build a vehicle-mounted thrust stand for dynamic testing
of propellers that could replace traditional wind tunnel testing methods.

## Approach

An elevated thrust stand [(RC Benchmark)](https://www.tytorobotics.com/pages/series-1580-1585) provided sufficient clearance for data collection. Airspeed was collected using a pitot tube and windvane to verify non-axial airspeed. Tests were conducted at the El Mirage Dry Lakebed in Adelanto, CA. 

<div class="row justify-content-sm-center align-items-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include video.liquid path="assets/video/drive_by.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
## Results

The data collected showed acceptable repeatability and qualitatively matched trends expected from literature data for propellers larger than 9 inches in diameter. By reducing the measured performance of the propellers into characteristic coefficients, results were compared to equivalent wind tunnel tests performed by [Deters and Selig](https://m-selig.ae.illinois.edu/pubs/DetersAnandaSelig-2014-AIAA-2014-2151.pdf). 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/prop_results.jpg" title="test_data" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Plots of thrust coefficient (left) and power coefficient (right) vs advance ratio. Experimental data was collected with the car-mounted thrust stand. Theoretical data comes from the work of [Deters and Selig](https://m-selig.ae.illinois.edu/pubs/DetersAnandaSelig-2014-AIAA-2014-2151.pdf).
</div>

