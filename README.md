# ProgrammingPractice

## 1 - Code and Description
### Code
https://github.com/Juan-Ignacio-Ortega/ProgrammingPractice/blob/main/PercolationCode_JIOG.py

### Description
https://github.com/Juan-Ignacio-Ortega/ProgrammingPractice/blob/main/PercolationDescription_JIOG.ipynb

## 2 - Introduction
Percolation is the study of the connectivity of random media and other properties of connected subsets of random media.

The porous media illustrated in the figure serve as a fundamental and useful model for random media in general. The porous medium consists of regions with material and without material, therefore it is an extreme binary version of a random medium.

An actual physical porous material will be generated by some physical process, which will affect the properties of the porous medium in some way. For example, if the material is generated by sedimentary deposition, the details of the deposition process may affect the shape and connectivity of the pores, or subsequent fractures may generate straight fractures in addition to rounder pores (Malthe, 2020).

In this activity, the aim is to find the critical percolation of a matrix that simulates an object which is to be traversed from top to bottom according to a certain probability of obstructed areas. For the aforementioned, the nearest neighbor connectivity will be used, with different priority considerations and size and movement constants, which will be explained little by little in each section. In addition to a structured programming in the form of a state machine, for a better understanding.

## 3 - Theoretical framework
Fig. 1 illustrates a porous material, a material with holes, pores, of various sizes.

![alt text](https://github.com/Juan-Ignacio-Ortega/ProgrammingPractice/blob/main/Fig1.1Percolacion.png?raw=true)

Figure 1. Illustration of a porous material from a nanoporous silicate (SiO2). The colors within the pores illustrate the distance to the closest part of the solid (Malthe, 2020).

Percolation is the study of connectivity. The simplest question we can ask is when does a path form from one side of the sample to the other?, and by when, they refer to what probability value (p.) a matrix m achieves this path. We see that the answer depends on how we define connectivity. If we want to make a path along a set figure from one side to the other, we must decide when and how two sites are connected. (Malthe, 2020)

## 4 - Reference
Malthe-Sørenssen, A. (2020). Percolation theory using Python. Department of Physics, University
of Oslo.
