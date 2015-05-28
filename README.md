# EvaluateCF
Source Code and Synthetic Data sets of A Framework to Evaluate the Performance of Collaborative Filtering in Recommendation Systems based on Binary Purchase Data

This repository contains seven main documents:
1)	Read Me.docx
2)	Synthetic Datasets folder
3)	Steering.R
4)	Programs folder
5)	Output folder
6)	Methods.txt
7)	Datasets_fin.txt

1)	Read Me.docx
This document containing an explication of different components in the folder.

2)	Synthetic Datasets folder
This subfolder contains all the 54 synthetic datasets used in the submission stored as tab-delimited text file. The image files (.jpg) contain a summary of characteristics of the related datasets. Due to privacy issues, the real-life data cannot be made publically available.

3)	Steering.R 
The main program controlling the execution of the different algorithm variations. The algorithm is written in R (v3.1.2). 
To run the algorithm: Set wd (working directory) and set parameters
Packages needed:
-	scales
-	sqldf
-	FNN
-	recommenderlab
-	NMFN
-	proxy
-	FactoMineR
-	Kendall
-	reshape2

4)	Programs folder
Contains all the programs called by the Steering.R program to execute distinct calculation tasks.

5)	Output folder
An empty folder towards which the output is redirected when the algorithms are calculated.

6)	Methods.txt
A tab-delimited text document containing a line for each individual algorithm variations that is calculated. By deleting individual lines, you can eliminate algorithms.

7)	Dataset_fin.txt
A tab-delimited text file containing the names of the (54) datasets for which the algorithm variations, defined in Methods.txt, are calculated.

