# CrowdSim

Pet project to play around with UnrealEngine AI.


I want to make a simulation of the crowd.
* On the first step I plan to use mostly UnrealEngine implementation. Their solutionm, as I understand, is game-oriented, so, designed to provide a nice looking behavior of sparced agents.
* I also want to control a quality of the solution, first by a simple model of taking damage on interactions.
* Having started with homogenous agents in quite simple situation, I want to make the scene more complex. E.g. by making crowd more dence and by adding more movement rules and irregularities
* There is two options for future development:
  1. Making movement behavior more realistic, with heuristics-based algorithm. So the simulation will be closer to a real crowd
  2. Finding optimal parameters for the existing algorightm with given scene parameters e.g. authomatically, using the genetic approach

  I'll choose this later. Before and even after this it is not desired to introduce any architecture-driven limitations, rejecting any of those paths

There is no particular final idea. Yet. Local plans are listed in [planning.md](https://github.com/sslebedev/CrowdSim/blob/main/planning.md).
