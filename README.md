# Sudoku_v2
Sudoku Solver version 2.0

Updates to Previous Version:

Added a Sudoku Detection Program that automatically detects the sudoku from an image and feed it to Sudoku Solver.

Files:

* Sudoku_Solver : This file contains functions to solve a sudoku puzzle 
* Sudoku_Solver_Main_v2 : This is the main file where I have used OpenCV library to process the Sudoku Image which then is feeded to my ML model for genration of grid recognisable by my Solver File.
* Utility_Functions : This contain all the utility functions used in my Sudoku_Solver_Main_v2 file
* digit_recog_main.h5 : ML model

Libraries Used:

* TensorFlow  version -- 2.5
* OpenCV      version -- 4.5.2 
* Numpy       verison -- 1.19.5
* Matplotlib  verison -- 3.4.2


For the ML model, I have chosen the simillar architecture as of LeNet (developed by Yann Lecunn).

If having problem in viewing the ipython notebook refer here:

* Sudoku_Solver_Main_v2 --> https://nbviewer.jupyter.org/github/Arsh-D-Vijay/Sudoku_v2/blob/main/Sudoku_Solver_Main_v2.ipynb
* Sudoku_Solver --> https://nbviewer.jupyter.org/github/Arsh-D-Vijay/Sudoku_v2/blob/main/Sudoku_Solver.ipynb
* Utility_Functions --> https://nbviewer.jupyter.org/github/Arsh-D-Vijay/Sudoku_v2/blob/main/Utility_Functions.ipynb


Things to work on in future:

* Better Accuracy.
* Better Detection Technique.
* View solved sudoku on screen feature.
* Make an interactive app.
