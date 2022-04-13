======
Readme
======

Collection of pre-processing tools for Mesh2HRTF.

EvaluationGrid
==============

Python, Matlab/Octave, and Blender Tools for generating custom evaluation grids
for Mesh2HRTF

MeshGrading
===========

C++ tools for grading (remeshing) a mesh before using it for numerical
calculations. Grading reduces the number of faces in a mesh and thus decreases
the time of the numerical calculations.

**Hybrid (recommended):** Mesh grading based on the local curvature and distance
from the ear as described by Palm et al. [1].

**Distance Based (not maintained):** Distance based mesh grading as described
by Ziegelwanger et al. [2].

MeshManipulation
================

Python scripts for centering a head mesh and assigning materials using Blender.

References
==========

1 T. Palm, S. Koch, F. Brinkmann, and M. Alexa, "`Curvature-adaptive mesh
  grading for numerical approximation of head-related transfer functions
  <https://www.researchgate.net/publication/280007918_MESH2HRTF_AN_OPEN-SOURCE_SOFTWARE_PACKAGE_FOR_THE_NUMERICAL_CALCULATION_OF_HEAD-RELATED_TRANFER_FUNCTIONS>`_", in Fortschritte der Akustik – DAGA 2021
  (Vienna, Austria, 2021) pp. 1111–1114.

2 H. Ziegelwanger, W. Kreuzer, and P. Majdak, "A-priori mesh grading for the
  numerical calculation of the head-related transfer functions," Appl. Acoust.
  114, 99–110 (2016). doi:`10.1016/j.apacoust.2016.07.005 <https://doi.org/10.1016/j.apacoust.2016.07.005>`_
