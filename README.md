# mu3e-light-new-physics
New light physics at Mu3e corresponding to the code written for arXiv:xxxx.xxxxx.

This repository contains the UFO model files for our various signal models plus also our modified MadGraph script used to splice together various windows in the electron-positron pair invariant mass. 

## Madgraph script
the "cuts.f" file is a slightly edited version of the default "cut.f" file in Madgraph. Our main edits are between lins 449 and 470, where we implement a cut requiring that at least one e+e- pair has an invariant mass smaller than MAXMEECUT and larger than MINMEECUT. These variables have to be set to a numerical value before running madgraph.

## UFO models
The UFO models we used are also included, where we used separate models for the (pseudo)-scalar, vector and flavor violating scalar cases.
