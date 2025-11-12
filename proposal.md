# Proposal

## Topic
Smoothed Particle Hydrodynamics (SPH) methods for Fluid Simulation

## Motivation

## Background

## Experiments to run
Dam Break, SPH, WCSPH, EDAC, IISPH
Optionally: Pipeflow, oscillating drop, moving wall

## What data will we collect?
* Solve/runtime time
* Memory usage per run
* Variance in math formulas used
* Error? using different simulations
* Scaling, runtime vs num particles?
* Accuracy/numerical stability
* How is the package calculating acceleration/velocity/pressure 

## Who's doing what
* Jesse: start experimenting with the Dam Break, want to see what we can relate with the time integration solver vs class topics
* Alan: Taylor Green vortex (error based time step control), how is the package calculating acceleration/velocity/pressure
* Ishita: Pipeflow or oscillating drop or moving wall.
* Patrick: look into viscosity/pressure equations or gathering timing/scaling data or look into papers that have used trixi for simulations (you can also do whatever you want patrick just update this :) !!)

## Extensions
* GPU parallelization 

## Timeline?
End of this week: is 1 or 4 experiments viable. thinking about what we can change, and how, for each experiemnt. Think about the merit of changing various parameters.
Next week: data collection and work on presentation (15 min, jupyter notebook) and paper (2-5 pages, .tex file in repo)
Presentation: December 3rd

## Deliverables
* Paper - tie it back to the class!!
* Presentation
* Videos of simulations

## References

