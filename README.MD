# CS466 Final Project Hirschberg Fitting Alignment Problem
This project was completed as part of the final project for CS466, Intro to Bioinormatics, at the University of Illinois Urbana Champaign. It is a demonstration and validation of the Hirschberg Algorithm. The problem being addressed is a Linear-Space Fitting Alignment Problem. The authors of this project are Franklyn Wu and Priya Kumar.

## Requirements and Installation
This project was written on Jupyter Notebook and requires a Python enviornment to execute correctly. The specific version used during development was 3.9.13, but the application may work for other Python versions. The application also requires the importation of the Python packages nose.tools and numpy. Otherwise, this project requires no additional installations besides the repository files themselves. To run the main portion of the project, open the main deliverable "Fitting_Hirschberg.ipynb" and run the Jupyter Notebook file.

## Main Deliverable: "Fitting_Hirschberg.ipynb"
The main deliverable is a Jupyter Notebook file titled "Fitting_Hirschberg.ipynb", loosely formatted in the form of a CS 466 Homework assignment. Functions, calls, inputs, and unit tests are all located within this file, as the main purpose of the overall project is to fully demonstrate the algorithm's implementaiton. Within the file are detailed markdown notes describing the rationale behind the implementaiton of each subroutine, as well as comments within the code itself. 

All subroutines within "Fitting_Hirschberg.ipynb" are novel and written by the authors of this project with two exceptions, listed below.

1) The section labelled "Testing Function- Normal Fitting Alignment" was sourced from coding portion of the first CS466 2023 Homework Assignment. This was done for the purpose of providing the user an additional means to analyze the performance and output(s) of the authors' implementated subroutines. However, it is not actually used in the implemented solution in any way. Thus, the authors do not consider this section an actual part of the project, unlike the other subroutines in the file. It is included for user convinience. 

2) Due to time constraints, certain input variables were reused or slightly modified from the first CS466 2023 Homework Assignment. These include short and reference sequences, as well as scoring funcitons. This reduced the time it would take to create inputs manually for validation. 

For the rest of the file, code from the first CS466 2023 Homework Assignmentwas referenced, but all subroutines are newly written. 

## Secondary Deliverable
There is a secondary deliverable named "Fitting_Functions.py". It is a Python file containing all functions implemented by the authors, so they can be imported into other scripts or run from the command line. This is not considered part of the main project and is also included primarily for user convinience.

## Credits:
This project is primarily an implementation of the Hirschberg Algorithm, first published by Dr. Dan Hirschberg in 1975. 

The authors of this project would like to thank Dr. Mohammed El-Kebir and the CS 466 Course Staff for creating the homework assignment referenced for this project, and also for providing the conceptual explanation of the Hirchsberg Algorithm.
