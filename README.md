# Octave Notes

This repository contains a collection of notes on MATLAB/Octave using Jupyter Notebooks. These Notes will teach you some basics of MATLAB programming as well as some fundamental concepts in numerical computing, including:
 - Matrix in MATLAB
 - Interpolation
 - Solving Linear Equations
 - Optimization
 - Root Finding
 - Solving Ordinary Differential Equations

These notes are used in the numerical-science module of AMS 561 - Introduction to Computational Science at Stony Brook University.

To run these notebooks interactively, you need to set up some software packages on your computer. First, install Docker for your platform (Windows, MacOS, Linux, cloud platforms, etc.), follow the instructions at [docker.com](https://docs.docker.com/engine/getstarted/step_one/). Then, download this repository and start Jupyter Notebook using the command `docker-notebook` script in this reposito directory. For example, to open `octave-interpolation.ipynb`, use the following command in a terminal:
```
    ./docker-notebook octave-interpolation.ipynb
```
It will automatically download the Docker image, start Jupyer Notebook in the image, and open the notebook your web browser for you to run interactively. 

**Note**: The Docker image is about 1.7 GB, so you need to have a faster internet connection to download the image for the first time.