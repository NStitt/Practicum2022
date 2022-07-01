# Practicum2022
## These are the scripts used for my practicum to complete my Master's in biomedical informatics at the NYU Grossman School of Medicine’s Vilcek Institute of Graduate Biomedical Sciences.

## The two main focuses of this project was the tracking of cells in three-dimensional images and the interpolation of images within a z-stack 

## The scripts are assoicated with these focuses as follows: 

Cell Tracking
	
	Manual_Cell_Tracking.ipynb
		Main script for developing and testing CellTracker versions and related functions. 
	
	Compare_Mesmer_Labels.ipynb
		Script to compare the labeling performance between the final CellTracker version and Mesmer.
		
	Cell_Track_Measurements.ipynb
		Used to perform internal validation and compare between versions 3 and 4 of CellTracker
		
	Mesmer.ipynb
		Versions of functions to deploy Mesmer and calculate data. 
		
	Mesmer_Performance.ipynb
		Script for comparing the results of feeding interpolated images to Mesmer (Not completed). 

Z Interpolation

	z_interpolation.ipynb
		Main script for developing and testing z interpolation functions. 
		
	Run_Z_interpolation.ipynb
		Script for creating a modified version of the z interpoaltion and running it to interpolate new images in a z-stack instead of over existing images. 

Other

	Tif_Manipulation.ipynb
		Scratch script used to test reading in and working with tif images. 
		
	Cell_Tracking.ipynb
		Used to test Mesmer Cell tracking. 
