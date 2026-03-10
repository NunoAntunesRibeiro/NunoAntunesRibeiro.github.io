## Research Problem
Air cargo terminals play a critical role in global logistics, handling large volumes of cargo that must be temporarily stored before loading onto aircraft or transported to their final destinations. With the continuous growth of air cargo demand, airport terminals face increasing pressure on available storage space.

One particularly challenging problem concerns the assignment of **non-stackable cargo**, such as pallets or specialized containers that cannot be placed on top of each other. These items must be stored directly on the terminal floor, which significantly limits the available storage capacity and increases operational complexity.

Terminal operators must decide where to place each cargo unit while considering factors such as storage duration, cargo size, operational accessibility, and future retrieval operations. Poor storage decisions can lead to inefficient use of space, congestion in cargo handling areas, and delays in cargo processing.

## Contributions
Our research develops **optimization-based approaches to support storage planning in airport cargo terminals**, focusing on the efficient allocation of floor space for non-stackable cargo.

Key contributions include:

- A **time-dependent mixed-integer linear programming (MILP) formulation** for the cargo storage assignment problem
- A modeling framework that accounts for **arrival and departure times of cargo units**, ensuring feasible storage plans over time
- Objective functions that minimize wasted storage space while improving the **dispersion of cargo placement**, reducing operational congestion
- The development of a **logic-based Benders decomposition (LBBD) algorithm** to solve large-scale instances efficiently
- Computational experiments demonstrating strong performance on realistic instances, including scenarios with **up to 150 cargo units**

These approaches provide cargo terminal operators with analytical tools to better manage limited storage space and improve operational efficiency.

## Selected Publications
- [*Optimization of Storage Space Assignment at Airport Cargo Terminals*](https://www.sciencedirect.com/science/article/pii/S0377221726000755)  
  Li, M., Ribeiro, N. A., & collaborators. (2026). *European Journal of Operational Research.*

## Research Collaboration
This research is conducted in collaboration with **Northwestern Polytechnical University (China)**.
