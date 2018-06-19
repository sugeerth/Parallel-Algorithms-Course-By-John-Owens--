# Work on understanding the GPU #

[![Screenshot 2017-06-04 18.08.33.jpg](https://s15.postimg.cc/g6kbghyff/Screenshot_2017-06-04_18.08.33.jpg)](https://postimg.org/image/gjbpmogp3/)

### What is this repository for? ###

I am attaching three very essential projects that I worked on this course that I enjoyed learning.

1) This document contains our results for the investigation of the crossover
point between the geometry and the rasterization stages of the pipeline.We
use WesBench as our benchmark program to make the characterization under
different conditions. 

2) We discuss the essential parts of the
GPU hardware that makes it unique. The programs are written in PyCuda.
Python is simply used to set up the computation and the kernels which are in
C. 

3) Fluids are a common occurrence in real world applications, and considerable
work has been done on simulating fluids. The two major class of algorithms
for simulating fluid flows are grid-based (Eulerian grids) and particle-based
(Smoothed Particle Hydrodynamics). SPH has certain benefits over traditional
grid-based methods and is being increasingly used for fluid simulation. There
is a great deal of interest in porting SPH to GPUs to achieve real-time fluid
simulation. We will implement one such method and analyse its performance
on different GPUs under various settings.
