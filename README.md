Image Processing Lab - Computer Vision Tasks
This repository contains Python code for various image processing and computer vision tasks completed as part of Lab Assignment.
Tasks Completed
Task 1: Pixel Art Creation

Created pixel art representations of letters 'M', 'O' and numbers '0', '7'
Used NumPy arrays to define pixel patterns
Displayed using matplotlib with grayscale colormap

Task 2: Image Transformations

Cropping: Extract specific regions from images
Rotation: Rotate images by -90 degrees with scaling
Shearing: Apply geometric transformation
Flipping: Horizontal image flipping
Translation: Shift images by specified pixels

Task 3: Image Blending and Noise Addition

Blended multiple images with varying alpha values
Added Gaussian noise to blended images
Generated histograms for noise analysis

Task 4: Salt and Pepper Noise

Added salt and pepper noise to images
Analyzed noise distribution through histograms

Requirements
pythonimport numpy as np
import matplotlib.pyplot as plt
import cv2
import os
Usage

Update the file paths in the code to match your image directories
Run the Python script:

bashpython image_processing_lab.py
Features

Supports multiple image formats (PNG, JPG, JPEG)
Automatic directory creation for processed images
Visual comparison of original vs processed images
Histogram analysis for noise characteristics# CVS-INTRO
