# DAMASK - The Düsseldorf Advanced Material Simulation Kit

- Usage, installation, and support: https://damask.mpie.de
- Code development: https://git.damask.mpie.de
- General inquiries: damask@mpie.de

## DAMASK_EICMD

This is a DAMASK fork with implementation of the "Discrete Deformation Twinning Model" based on work done by Dr. Satyapriya Gupta and Dr. Philip Eisenlohr at MSU.

### The Discrete Deformation Twinning Model
The aim of this model is to accurately match experimental observations of deformation twinning while remaining computationally efficient compared to physics-based phase field models.

* We introduce stochasticity for the nucleation and growth events of twinning through random sampling, similar to Monte Carlo Methods.
* The ease or difficulty of a twinning event is controlled by adjusting the frequency of sampling.
* At each voxel, the state of twinning is treated as a discrete quantity, unlike the approach based on diffused volume fraction method.
* The kinetics of twinning occur in the form of a “jump,” rather than following a rate equation as in the “pseudo-slip” approach.
* The jumped state is evaluated using the correspondence matrix from Niewczas, Acta Materialia, 2010.

## Repository Locations

### [git.damask.mpie.de](https://git.damask.mpie.de)

All code development is centralized in the principal DAMASK code repository hosted at [git.damask.mpie.de](https://git.damask.mpie.de).
Access to this GitLab instance requires registration and is granted to anyone with an interest in actively supporting the development of DAMASK.

### [github.com](https://github.com)

GitHub hosts the publicly accessible, but read-only, mirror of the principal DAMASK code repository and replicates its three top-level branches from [git.damask.mpie.de](https://git.damask.mpie.de).

The site is primarily meant to provide a forum for [Discussions](https://github.com/eisenforschung/DAMASK/discussions) and [Issues](https://github.com/eisenforschung/DAMASK/issues).


## Contact Information

(
EICMD Team, IIT Dharwad
https://sites.google.com/view/eicmd/home
)

Max-Planck-Institut für Eisenforschung GmbH  
Max-Planck-Str. 1  
40237 Düsseldorf  
Germany  
