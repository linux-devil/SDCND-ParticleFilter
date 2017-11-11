# SDCND-ParticleFilter
Particle Filter implementation for Udacity Self Driving Car Engineer Nanodegree

Steps followed are:
1. Initialization step : Particles with initial position , orientation and noise are initialised.
2. Update step : Based on current particles, position, orientation and noise are updated.
3. For every particle find landmarks within sensor range
4. Transformation step: Particle position mapped to map coordinates
5. Weight calculation: Particle weights are calculated using landmark with vector distance and angle error.
6. Resampling of particle weights.
7. Repeat above steps for each observation
