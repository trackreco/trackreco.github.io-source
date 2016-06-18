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

The LHC collides proton beams at the center of our detectors
and, by measuring the energy and momentum of the escaping particles, we
infer the existence of massive particles that were created and
decayed in the pp collision and measure those massive particles’
properties.  In all cases, track reconstruction, i.e., the determination
of the trajectories of charged particles ("tracks") from a set of
positions of energy deposits from the various layers in our detector
("hits"), plays a key role in identifying particles and measuring
their charge and momentum. Track reconstruction, also known as
tracking, as a whole is the most computationally complex and time
consuming, most sensitive to increased activity in the detector,
and traditionally, least amenable to parallelized processing.

