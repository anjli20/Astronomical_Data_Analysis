Astronomical Data Analysis Project

This project demonstrates an end-to-end astronomy data science workflow using Python. It combines machine learning on tabular star data with FITS image processing of the Andromeda Galaxy (M31).
The notebook is designed to run automatically in Google Colab or Jupyter-style environments. The dataset and FITS image are fetched directly from online sources, so no manual local download is required.

Project Overview
The project contains two major parts:
Star Type Classification using Tabular Astronomical Data
M31 FITS Image Processing and Source Detection
The first part focuses on exploring a star dataset, creating visualizations, and training machine learning models to classify stars. The second part focuses on working with FITS image data, visualizing the Andromeda Galaxy, applying image scaling, detecting sources, and extracting image features.

Features

1. Star Type Classification
This section uses a tabular star dataset containing physical and categorical properties of stars.
It includes:
Automatic dataset loading
Data exploration and summary statistics
Missing value checking
Star type label mapping
Data visualizations
Correlation analysis
HR diagram generation
Machine learning preprocessing pipeline
Multiple model training and comparison
Cross-validation
Confusion matrix
Classification report
Feature importance analysis
Custom star type prediction

3. FITS Image Processing of M31
This section works with astronomical FITS image data of M31, also known as the Andromeda Galaxy.
It includes:
Automatic FITS image fetching using Astroquery and SkyView
FITS header inspection
WCS object creation
Raw image visualization
Pixel statistics
Image scaling and normalization
Background estimation
Background subtraction
Gaussian denoising
Source detection
Pixel-to-sky coordinate conversion
Aperture photometry
Segmentation map generation
Image filtering
Edge detection
Feature extraction
Multi-survey image comparison

Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Astropy
Astroquery
Photutils
Scikit-image
SciPy
OpenCV
Joblib

This project shows how Python can be used for both tabular and image-based astronomical data analysis.
It combines data visualization, machine learning, FITS image handling, source detection, photometry, and image feature extraction into one complete astronomy data science pipeline.
The project is suitable for learning, portfolio building, and as a starting point for more advanced astronomy data analysis projects.
