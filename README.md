# ADM_HW2
This repository contains the solutions to the questions of homework 2 for the course Algorithmical Methods for Data Science (2019/2020).


## main
*main.ipynb* is a notebook with all the solutions concerning the soccer analytics part, ordered in the same way they are presented in the assignment.

At the beginning all the *libraries* needed are imported. Then, each exercise begins with its *title* (in the form "[RQ<number>] <question>" or with CRQ in place of RQ) and it's organized with *subtitles* such as "Datasets", "Cleaning the data" - which are always present (we always take data and then keep only useful information for the current task) - and others, such as "Plotting the heatmap", which explain what's going to be done in the related section.
  
Answers and related comments are always the last part before the next Question or the end, while general comments are widely spread.


## theory
This contains the solution to the *Theoretical Question*.


## distribution_num_passes
This is also a notebook where we tried to see how where the number of passes distributed among Premier League's players, in order to have an idea about the minimum threshold choice. We argued that the arithmetic mean may not be a good solution, because players who did almost this number of passes are good to evaluate too, but we couldn't find a better idea which would have not been "too arbitrary" (e.g.: 2/3 of the arith. mean).

In addition to this, the data considered to take the average were only those of players who did at least one pass, while there are some who didn't do any and these are not taken into account.
