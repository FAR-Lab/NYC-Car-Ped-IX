# NYC-Car-Ped-IX
 
## Project Modules

- Digital Twin
  - A high fidelity model of a selected urban area in NYC
  - Detailed model on essential buildings and attractors
  - Populated with static elements including light poles, trash cans, traffic lights, etc.
- Interaction Controllers
  - Pedestrian controller that allows participants to walk around and "teleport" to next area of interest
  - Car controller that allows participant to drive a car in VR
  - Full body tracking
  - Multiplayer support
- Simulators
  - Pedestrian simulator that populates the sidewalks with pedestrians
  - Car simulator that populates the streets with moving cars

## Simulators

### Pedestrian Simulator

A global controller that controls all pedestrians
- PedSimController

In each individual pedestrian
- PedBehaviorController
- PedNavigator
- PedAnimator

### Car Simulator
