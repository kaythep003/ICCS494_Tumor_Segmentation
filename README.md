# Brain MRI Tumor Detection and Segmentation (Pair work)

## Overview

Developed an image-processing pipeline for detecting and analyzing brain tumors from MRI scans. The project combines denoising, skull stripping, region-based segmentation, and heatmap visualization to identify potential tumor regions in brain MRI images.

## Technologies

* Python
* OpenCV
* NumPy
* PyWavelets
* SimpleITK
* Matplotlib
* Jupyter Notebook

## Key Tasks

* Collected MRI brain scan images from a public dataset
* Preprocessed images through grayscale conversion and resizing
* Applied wavelet-based denoising using discrete wavelet transforms
* Implemented skull stripping using thresholding and morphological operations
* Developed seed-based tumor segmentation using Connected Threshold algorithms
* Extracted tumor boundaries using gradient magnitude analysis
* Generated density and distance heatmaps to visualize tumor characteristics

## Features

* MRI image preprocessing
* Wavelet noise reduction
* Automated skull removal
* Tumor region segmentation
* Edge and texture analysis
* Heatmap visualization for tumor assessment

## Results

* Successfully isolated brain regions from MRI scans
* Detected and segmented tumor candidates in both clear and low-contrast images
* Visualized tumor structures through gradient and density-based heatmaps

## Skills Demonstrated

* Computer Vision
* Medical Image Processing
* Image Segmentation
* Feature Extraction
* OpenCV
* Scientific Computing

