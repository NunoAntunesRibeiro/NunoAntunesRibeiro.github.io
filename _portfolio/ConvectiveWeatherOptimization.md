---
title: "Optimization of Aircraft Trajectories in Terminal Airspace under Convective Weather"
excerpt: ""

collection: portfolio
---

## Research Problem
The **terminal airspace** surrounding airports is one of the most complex and safety-critical regions of the air transportation system. It is the area where aircraft arriving and departing from an airport converge and diverge, requiring precise coordination to maintain safe separation between flights.

Under normal conditions, aircraft follow predefined procedures known as **Standard Arrival Routes (STARs)** and **Standard Instrument Departures (SIDs)**. These structured routes simplify air traffic control and allow aircraft to be sequenced efficiently into the runway system.

However, during **convective weather events** such as thunderstorms, these standard routes may become partially unavailable or unsafe to use. Aircraft may need to deviate from their planned trajectories, enter holding patterns, or be rerouted through alternative paths that avoid hazardous weather cells. Managing these deviations while still maintaining safe separation and efficient traffic flow presents a significant operational challenge for air traffic controllers.

## Contributions
Our research develops an integrated framework that combines **machine learning, trajectory planning, and optimization algorithms** to support aircraft operations in terminal airspace under convective weather conditions.

Key contributions include:

- **Deep learning models (CNNs)** for short-term nowcasting of convective weather probability using radar-based weather data
- A **multi-objective A\* trajectory planning algorithm** that identifies alternative flight paths that minimize exposure to convective weather
- A trajectory planning approach that allows aircraft to **remain close to their original STAR/SID procedures when possible**, while allowing deviations when needed
- Optimization models that balance **weather avoidance, flight distance, and operational feasibility**
- A sequencing optimization algorithm that determines the **optimal arrival order and timing of aircraft** given the set of feasible trajectories generated in the previous step

This integrated framework enables more efficient and safer management of aircraft operations during disruptive weather events.
