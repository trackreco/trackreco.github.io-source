Title: 
date: 2016-06-17 10:53
save_as: index.html
Authors: Peter Elmer
Summary: Parallel Kalman Filter Tracking Reconstruction
Template: homepage

The [Large Hadron Collider (LHC)](https://home.cern/topics/large-hadron-collider)
at [CERN](https://home.cern/) is the highest energy
collider ever constructed. It consists of two counter-circulating
proton beams made to interact in four locations around a 27 kilometer
ring straddling the border between Switzerland and France. It is
by some measures the largest man-made scientific device on the
planet. The goal of the LHC is to probe the basic building blocks
of matter and their interactions. For example, in 2012, the Higgs boson 
was discovered by the [CMS](https://home.cern/science/experiments/cms) and
[ATLAS](https://home.cern/science/experiments/atlas) collaborations.

The LHC collides proton beams at the center of our detectors.
By measuring the energy and momentum of the escaping particles, we
infer the existence of massive particles that were created in the collisions
and measure the massive particles’ properties based on their decay products.
The determination of the trajectories of charged particles 
("tracks") from a set of positions of energy deposits from the various layers 
in our detector ("hits") plays a key role in identifying particles and 
measuring their charge and momentum. This pattern recognition
problem&mdash;known as "track reconstruction" or simply "tracking"&mdash;is
as a whole the most computationally complex and time-consuming step in the
measurement process, as well as the most sensitive to increased activity in 
the detector, and traditionally, the least amenable to parallelized 
processing.

This project aims to develop fully vectorized and parallelized tracking
algorithms based on the Kalman Filter for use in a collider experiment.
The software will be usable with parallel architectures such as Intel Xeon
processors and NVIDIA GPUs, yet maintain and extend the physics performance 
required for the challenges associated with the High Luminosity LHC (HL-LHC)
planned for the 2020s.

The project also initiated training for young researchers through the first
[dedicated school on tools, techniques and methods for Computational and Data
Science for High Energy Physics (CoDaS-HEP)](http://codas-hep.org). The
CoDaS-HEP school provides a broad introduction to these critical skills as
well as an overview of applications in High Energy Physics. Specific
topics covered at the school include: Parallel Programming, Big Data Tools
and Techniques, and Machine Learning Technology and Methods, as well as a
variety of practical skills. The inaugural CoDaS-HEP school took place on
[10-13 July, 2017](https://indico.cern.ch/event/625333/) at Princeton
University. Subsequent schools took place on 
[23-27 July, 2018](https://indico.cern.ch/event/707498/) and
[22-26 July, 2019](https://indico.cern.ch/event/814979/timetable) at
Princeton University.

Starting in 2018, this project became integrated into **IRIS-HEP**, the
Institute for Research and Innovation in Software for High Energy Physics.
The latest status of what is now called the **mkFit** project can be found at
the [mkFit project page](https://iris-hep.org/projects/mkfit.html) on the
[IRIS-HEP website](https://iris-hep.org).
