# Calibration light scattering - cell diameter
The goal of this project is to use an optimized Mie theory to infer particle cell size from forward scatter measurements. In order to use Mie theory, an optimization method was developed to minimize the difference between forward scattering measured by SeaFlow and estimated using Mie theory. The optimization step was necessary because the optical geometry of the flow cytometer is not precisely known. An optimization procedure was conducted to scale the dimensionless values of forward scatter, in which the differences between the Mie-modeled and measurement-derived forward scatter were minimized. We used SeaFlow measurements of calibration particles of known refractive index and size. These particles includes 7 sizes of polystyrene beads (0.3, 0.5, 0.75, 1, 1.83, 3.1 and 5.7 µm in diameter; n = 1.6003). Using this optimization, a lookup table of theory-based solutions for particle forward scattering was created over a range of particle diameter detectable by the SeaFlow (0.3 - 10 µm) and index of refraction applicable to marine phytoplankton (n=1.031 +/- 0.017).

![alt text](Mie-beads-scatter.png "SeaFlow forward scatter measurements compared to optimized Mie theory")

To evaluate the applicability of these solutions, we compared Mie-predicted cell diameter to observations (using a Coulter Counter) of numerous phytoplankton cultures.
![alt text](Size-scatter.png "Mie-predicted cell diameter compared to observations (using Coulter Counter)")

***François Ribalet, Megan Schatz and Jarred Swalwell contributed to this project.***
