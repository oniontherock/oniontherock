# Orion Martin

Hi, I'm Orion Martin. On my GitHub you can find most of my personal programming projects. I've made a fully functional game engine/framework in C++ on top of the SFML library, several swarm-intelligence simulations, and some experimental projects listed below. Recently my focus has shifted toward more physical systems (robotics, AI vision, etc.), but this GitHub is the foundation I laid before moving into robotics.

## Projects

**[ACECS-Engine](https://github.com/oniontherock/ACECS-Engine)**
An Entity-Component-System framework I wrote in C++. It handles events, input mapping, rendering layers, level management, and save/load. I built it so I could reuse the same core across different simulations instead of redoing all the plumbing every time. It's the biggest thing here and the one I'm most proud of.

**[Screaming Insects](https://github.com/oniontherock/Screaming-Insects-Simulation)** and **[Ant Simulation](https://github.com/oniontherock/Ant-Simulation)**
Agent-based simulations running on the engine above. Mostly experiments in getting a lot of small entities to move and behave in interesting ways.

**[Opticus](https://github.com/oniontherock/Opticus)**
An experimental non-Euclidean environment simulator, built in C++ using compute shaders.

**[Firebrand](https://github.com/oniontherock/Firebrand)**
A recreation of Opticus that moved away from non-Euclidean environments toward a more game-like style. I never finished it.

**Game AI (C#)**
A few smaller projects working through classic game-AI algorithms:
- [GOAP-Project-3.0](https://github.com/oniontherock/GOAP-Project-3.0), goal-oriented action planning
- [Flow-Field-Project](https://github.com/oniontherock/Flow-Field-Project), flow-field pathfinding
- [Boid-Project-CS-Remake](https://github.com/oniontherock/Boid-Project-CS-Remake), boids and flocking

These overlap a lot with the robotics topics I'm into now (planning, pathfinding, multi-agent behavior).

## What I'm working on now

A teleoperation setup for a Universal Robots arm: I track my hand with MediaPipe and drive the arm through ur_rtde, testing against URSim before touching real hardware. It's not on GitHub yet, but it's where most of my time is going right now. I also built a working digital clock as a 4-layer PCB out of TTL chips for one of my classes.

## Contact

The easiest way to reach me is through GitHub:
- Open an issue on a repo if it's about that specific project
- Or email me at orionmartin049@gmail.com
