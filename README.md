# zhqcs6208
# Code for Graph Network-based Simulators

This repository contains code for the implementation of the Graph Network-based Simulators (GNS) method, as described in the paper *[Learning to Simulate Complex Physics with Graph Networks]*. The code is written in Python and can be run in Google Colab. 

## Code versions

There are three versions of the code available in this repository:

- **baseline**: The original version of the GNS method described in the paper.

- **20layers**: A version in which the number of GN layers is increased from 10 to 20, demonstrating that increasing the number of GN layers alone does not improve the performance.

- **Improvement**: A version in which the structure of the GN layers is changed while keeping 10 layers. This version has 1/3 fewer parameters than the 20layers version but better performance.
