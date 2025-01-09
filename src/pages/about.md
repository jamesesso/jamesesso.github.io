---
layout: ../layouts/AboutLayout.astro
title: "About Me"
---

Hi, I'm James, and I have recently finished my PhD (just pending corrections).
My research focused on developing new methods for mesoscale simulation, with a view towards developing fast and accurate models for aggregating systems found in soft matter, such as surfactant solutions, gels, and biological systems.
I would describe my role as a combination of both that of a computational scientist and a software engineer. Through my PhD I have developed a love for all things simulation, high-performance computing (HPC), and low-level software development. I also have a love of all things science in general.

## My PhD Research

My research focuses on developing new methods for mesoscale simulation.
In particular, these systems are too large for all-atom molecular simulation, but at the same time, faster techniques such as traditional dissipative particle dynamics (DPD) produce poor predictions of the thermophysical properties.
My goal was to investigate a class of potential that is similar to dissipative particle dynamics yet incorporates information from a highly accurate equation of state into the potential.
This yields a potential with similar numerical properties to the DPD potential, while being able to achieve quantitative predictions of the thermophysical properties at the same time.

## My Skills

### Programming Skills

- **C++**: Much of my work has been in developing new simulation methods and this has been mostly using C++.
  I have developed an in house Monte-Carlo code for the exploration of new potentials, which includes several free-energy methods, multiple ensembles and a flexible design for rapid experimentation.
  In addition, I have incorporated my research into the parallel LAMMPS molecular dynamics package, which includes acceleration of some of the calculations with a Neural Network.
- **Python**: Throughout my PhD I have used Python daily for scientific computing. This includes pre and postprocessing simulations, managing complicated simulation workflows and some experience with machine learning with PyTorch and scikit-learn.
  I also used the C API to modernize older Fortran and C codes in the department.
- **Rust**: Rust is great! Many of my personal projects are in rust and it is something I hope takes off in the HPC space.
- **Basic HTML, CSS, and JavaScript**: I have some experience with web technologies including React, Electron and Astro. I have used these to produce interactive data visualizations and dashboards.
  I am also looking at using WebAssembly for fast simulations through the web.
- **Other Languages I have experience with**: Julia, Matlab and Fortran.
- **Tools, Libraries and Frameworks I have used**: Git, GitHub Actions, Bash, Docker, Singularity/Apptainer, Numpy, Scipy, Pandas, PyTorch, scikit-learn, MPI, HDF5, Signac, Eigen, Sphynx, Doxygen

### Scientific Skills

- **Molecular and Mesoscale Simulation:** The majority of my research has focused on molecular/mesoscale simulation. I have worked with both LAMMPS and DL_POLY extensively and produced custom Monte-Carlo simulations too.
- **HPC Usage:** I have used HPC systems daily throughout my PhD, including some relatively complex workflows. I have used SLURM and SGE extensively for batch job submission and Python, Bash and Signac for workflow management. Further, I have used Apptainer (Singularity) and Docker for containerization.
- **Statistical Mechanics and Liquid State Theory:** In addition to my computational research, I have also performed some theoretical investigation. In particular, in our first paper, we show that classical DFT can be an effective technique for calculating the interfacial and structural properties of soft equation of state based potentials.

## My Publications

- Local density dependent potentials for an underlying van der Waals equation of state: A simulation and density functional theory analysis. <ins>James P. D. O’Connor</ins>, Joanne L. Cook, Ian P. Stott, Andrew J. Masters, Carlos Avendaño. _Journal of Chemical Physics_ (https://doi.org/10.1063/5.0171331)
- Second paper accepted in the Journal of Physical Chemistry B, awaiting publication.
