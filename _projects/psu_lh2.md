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

Environmental commitments for reducing the environmental impact of aviation primarily rely on Sustainable Aviation Fuel (SAF). Long-term environmental commitments require transition from biofuels to a subset of SAFs known as power-to-liquid fuels (PtL SAF). PtL SAF requires renewable electricity, hydrogen produced by water electrolysis(green hydrogen), and carbon monoxide produced from atmospheric CO2. Liquid hydrogen (LH2) requires cryogenic tanks that present complex integration challenges.

The primary question remains: Should hydrogen be a component of future SAF production or should hydrogen itself be the primary aircraft propulsion fuel?   


## Approach

A conceptual design optimization framework for analyzing aircraft fueled
by SAF or LH2 is developed using [GPkit](https://gpkit.readthedocs.io/en/latest/) to explore the tradeoffs in environmental and economic performance of alternative fuels. Models of well-to-wake environmental impact and operating cost are implemented to quantify the impact of conventional jet fuel (Jet-A), SAF, and LH2.

## Results 

Two sets of aircraft designs are presented, based on a regional turboprop similar in
performance to a DHC-8-200 and a single-aisle transport similar to a 737-8. Integrating
LH2 tanks into the fuselage results in increased fuselage length and landing gear mass.
Energy consumption increases 3% for regional turboprop and 11% for single-aisle aisle
with LH2 compared to with Jet-A or SAF.

<div class="row align-items-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/q200_lh2_2view.png" title="Q200 LH2" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-md-7 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/737_lh2_2view.png" title="737 LH2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Cryogenic hydrogen tanks are integrated aft of the passenger cabin. Landing gear length increases to accomodate the increased fuselage length. 
</div>


The results show that both SAF and LH2-powered aircraft can have reduced CO2-equivalent emissions relative to today’s Jet-A aircraft, 43% for SAF and 57–60% for LH2, but at increased operating costs, 42–73% for SAF and 30–61% for LH2. Assumed fuel characteristics drive differences between SAF and LH2 aircraft. LH2 is assumed to produce 32% less CO2-equivalent emissions and cost 21% less than an energy-equivalent mass of SAF. Relative to the SAF configuration, the LH2-powered aircraft has reduced CO2-equivalent emissions, 30% for regional turboprop and 25% for single-aisle, and reduced operating costs, 9% for regional turboprop and 7% for single-aisle. When considering uncertainties in emissions from fuel production and the warming impact of contrails, LH2 and SAF aircraft have similar emissions and cost impacts relative to Jet-A aircraft.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/pareto_comparison.png" title="Future scenarios" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    With uncertainty, SAF/LH_2 have similar emissions/cost impacts. Additional research required to quantify relative impact of Jet-A, SAF, LH_2 contrails. 
    
</div>

For more information, refer to our publications {% cite vanlandingham2024environmental %} {% cite vanlandingham2023conceptual %}. 


