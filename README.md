# Python-code-for-visualizing-magnetic-field

The code simulates the trajectory of a charged particle in a uniform magnetic field using the Lorentz force equation.

First, the parameters of the magnetic field are defined, including the magnetic field vector B, the charge of the particle q, the mass of the particle m, the initial velocity of the particle v0, and the initial position of the particle r0.

Next, the simulation parameters are defined, including the maximum simulation time tmax and the time step dt.

The position and velocity of the particle are initialized to their initial values, and lists are initialized to store the particle positions and times.

Then, the simulation is performed using a while loop. In each iteration of the loop, the Lorentz force on the particle is calculated using the cross product of the velocity and magnetic field vectors, and the acceleration of the particle is calculated using the Lorentz force and the mass of the particle. The velocity and position of the particle are updated using the acceleration and time step. The particle position and time are then appended to their respective lists.

Finally, the magnetic field lines are plotted in a 3D plot using the plot() function of the Axes3D object in matplotlib.

The resulting plot shows the trajectory of the charged particle in the magnetic field, which appears as a helix-like shape around the magnetic field vector B.
