Title: 
date: 2016-06-17 10:53
save_as: index.html
Authors: Peter Elmer
Summary: Parallel Kalman Filter Tracking Reconstruction
Template: homepage

The [Large Hadron Collider (LHC)](http://home.cern/topics/large-hadron-collider) at [CERN](http://home.cern/) is the highest energy
collider ever constructed. It consists of two counter-circulating
proton beams made to interact in four locations around a 27 kilometer
ring straddling the border between Switzerland and France. It is
by some measures the largest man-made scientific device on the
planet. The goal of the LHC is to probe the basic building blocks
of matter and their interactions. For example, in 2012, the Higgs boson 
was discovered by the [CMS](http://cms.web.cern.ch) and 
[ATLAS](http://home.cern/about/experiments/atlas) collaborations. 

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

This project aims to develop tracking algorithms based on the Kalman Filter 
for use in a collider experiment that are fully vectorized and parallelized.
These will be usable with parallel processor architectures such as Intel's 
Xeon Phi and GPUs, but yet maintain and extend the physics performance 
required for the challenges for the High Luminosity LHC (HL-LHC) planned
for the 2020s.

The project also provides training for young researchers through a [dedicated 
school on tools, techniques and methods for Computational and Data Science
for High Energy Physics (CoDaS-HEP)](http://codas-hep.org). The CoDaS-HEP 
school provides a broad introduction to these critical skills as
well as an overview of applications High Energy Physics. Specific
topics to be covered at the school include: Parallel Programming,
Big Data Tools and Techniques, Machine Learning Technology and
Methods as well as practical skills. The first CoDaS-HEP school
took place on [10-13 July, 2017, at Princeton University]
(https://indico.cern.ch/event/625333/). The second CoDaS-HEP school
took place on [23-27 July, 2018, at Princeton University]
(https://indico.cern.ch/event/707498/).

