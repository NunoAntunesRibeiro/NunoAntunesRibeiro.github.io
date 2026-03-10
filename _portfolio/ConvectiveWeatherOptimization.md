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

## Analytical Framework
The proposed framework combines three key components:

1. **Weather Prediction**  
   Convolutional Neural Network (CNN) models generate short-term forecasts of convective weather probability in the terminal airspace.

2. **Trajectory Generation**  
   A multi-objective A\* search algorithm generates alternative aircraft trajectories that:
   - minimize exposure to convective weather
   - remain close to standard procedures when feasible
   - avoid excessive increases in flight distance

3. **Traffic Sequencing Optimization**  
   An optimization model determines the optimal sequencing and scheduling of aircraft within the terminal airspace based on the set of feasible trajectories.

## Expected Impact
The proposed methods support more resilient terminal airspace operations by:

- reducing delays during severe weather events
- minimizing fuel consumption caused by inefficient rerouting
- improving the safety of aircraft trajectories around convective weather
- supporting decision-making for future **trajectory-based operations (TBO)** in air traffic management.
