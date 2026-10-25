   # project_numalg
   Numerical methods project: 
   II. Orbital motion: 3-body problem
  

Introduction to numerical algorithms – semester project

Szabó Blanka & Fehér Adél

Topic: 
We simulate the motion of a planet orbiting a star under Newtonian gravity.
The motion is described by a system of ordinary differential equations, which
we solve with numerical methods. The two-body problem also has an exact
(Kepler) solution, so we can check how accurate our numerical results are.

Goals: 
- Implement numerical methods for the equations of motion
  (e.g. Euler's method, Runge–Kutta 4, velocity Verlet).
- Compare their accuracy and stability, for example by checking how well
  they conserve energy over many orbits.
- Plot the orbits and compare them with the exact elliptical orbit.

Files: 
- `orbitalmotion.ipynb` – main notebook with the code, plots and explanations.