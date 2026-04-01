# Overview
This project uses neural networks to learn the orbital motion of celestial objects, and their relationships. The ideal goal of this project is to use machine learning to derive Newton's law of gravitation. 

# Phase 1 - singular orbit
A neural network which takes position coordinates of an object (in this instance, Mars) as inputs and outputs its velocity vector, implicitly learning its orbital path. This model is trained off 50 years of Mars's orbital data.

# Phase 2 - neighbors
A neural network which takes the position and velocity vectors of Mercury, Venus and Mars as inputs and outputs the position and velocity vectors of Earth. Characterizes the relationship between nearby orbits. 