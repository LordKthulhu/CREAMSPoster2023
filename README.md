# Hydration-based multi-physics modelling of cementitious materials for 3D printing

Supplementary material for the 33rd ALERT Workshop poster session.  
The digital version of the poster is available in this repository.

Author's contact:  
Maxime PIERRE  
[maxime.pierre@enpc.fr](mailto:maxime.pierre@enpc.fr?subject=Question%20about%20your%20ALERT%20Poster)  
[LinkedIn Profile](www.linkedin.com/in/maximepierre-enpc)

## Extrusion-based 3D printing with cement-based materials

This is a video shows an example printing at Navier laboratory:

https://github.com/LordKthulhu/ALERTPoster2023/assets/31048121/a2a71b98-2c82-44d4-ab62-aef8ccd44f66

The unfortunately collapsed resulting structure can be seen at the top left of the poster.

## Simulation of the printing process

An example simulation of a 3D-printed cylinder with magnified deformation. One can see the sequential deposition of the material, 
as well as the passage of the printer's nozzle applying pressure on the section currently being printed.

https://github.com/LordKthulhu/ALERTPoster2023/assets/31048121/172bf053-b372-42fb-b4bc-32f4b970ea4f

Simulations are performed through our own code based on open-source codes: [Gmsh](https://gmsh.info) for meshing, [MFront](https://thelfer.github.io/tfel/web/index.html) for constitutive law integration and [FEniCS](https://fenicsproject.org) for the finite element part.

## Failure modes: 2D-axisymmetric illustration

Below is an axisymmetric simulation of the corolla geometry with printing speed $v_{\rightarrow}=2$ cm/s. Notice how due to the geometry, plastic failure does not occur at the bottommost layer.

https://github.com/LordKthulhu/ALERTPoster2023/assets/31048121/260d8bf7-e377-41e8-85c6-bef1043ed03b

This is concordant with live printings where corollas tend to fail in their upper part while the lower layers stay intact (see illustration below).

![Corolla Failure](https://github.com/LordKthulhu/ALERTPoster2023/assets/31048121/2ceffc47-d0be-4a3a-91af-ec446f6e9c60)



