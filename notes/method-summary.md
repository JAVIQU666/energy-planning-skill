# Method Summary

## Problem

Integrated community energy systems combine electricity, heating, cooling, gas, renewable generation, storage, and flexible demand. Planning must handle renewable uncertainty, multi-energy load uncertainty, equipment failures, and computational growth from many normal and N-k contingency scenarios.

## JPER model

JPER means joint planning of economy and reliability. The model minimizes annualized investment cost, operation cost, and reliability cost. Reliability cost is represented through load shedding penalties, so reliability is co-optimized rather than checked only after economic planning.

## System scope

The modeled ICES coordinates PV, wind turbine, CHP, air source heat pump, ground source heat pump, gas boiler, electric boiler, absorption chiller, electric chiller, electrical energy storage, thermal energy storage, cooling energy storage, and integrated flexible load.

## Flexible load

Integrated flexible load includes basic load, shiftable load, and curtailable load. Flexible load supports renewable accommodation and reliability by shifting or reducing demand during stressful operating periods, reducing unnecessary storage investment.

## L-shaped decomposition

The planning problem is decomposed into a master planning problem and operational subproblems. The master problem selects investment decisions. Subproblems evaluate operation and reliability costs under normal and contingency scenarios and return cuts to the master problem.

## State similarity

The state similarity method identifies scenario subproblems that share the same optimal-basis structure. One representative scenario is solved directly, and other scenarios in the same state-similarity set are derived through linear equations. This keeps the massive scenario set while avoiding the accuracy loss of ordinary scenario reduction.

## Positioning

Compared with economy-only planning, this method embeds reliability cost in the objective. Compared with post-planning reliability assessment, it co-optimizes reliability from the beginning. Compared with scenario reduction, it avoids discarding scenarios. Compared with robust optimization, it is less worst-case conservative and uses scenario-based reliability evaluation.
