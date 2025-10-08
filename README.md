#TFCB Homework 1

Due Date: October 9th, 2025
Author: Benjamin C. Brim
Contact: bbrim@uw.edu

##Overview

This homework repository contains data on different species of ants, their measurements, and code to predict the species of ant based on inputs.

##Repository Organization

All data in its original organization can be found in the "messy-project-directory" found [here](https://github.com/brimbenj/tfcb-homework1/tree/main/messy-project-directory).

The original files have also been renamed put into more organized files including [code](https://github.com/brimbenj/tfcb-homework1/tree/main/Code) , [Data](https://github.com/brimbenj/tfcb-homework1/tree/main/Data), and [Images](https://github.com/brimbenj/tfcb-homework1/tree/main/Images)

##Data Structure

The original survey data [file](Data/survey_data_original.xlsx) is before cleaning. The cleaned data [file](LINK) has been altered to make the data tidy. All blank cells have been converted to NA values. Any observation where the scale was not calibrated has an NA value under weight as the values cannot be trusted.

The data contained in the survey data file contains the following variables:
-Date Collected (YYYY-MM-DD)
-Plot #
-Sex
-Weight (in grams)
-Species

An example observation appears like this:
|date_collected|plot|sex|weight|species|
|:---:|:---:|:---:|:---:|:---:|
|2014-01-09|1|M|40|DM|

An example image looks like this:
![An Camponotus Darwinii curled up with a scale bar of 1mm](Images/casent_0191696_Camponotus_darwinii.jpg)
