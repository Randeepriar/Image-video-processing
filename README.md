# Image and Video Processing

This repository contains my Image and Video Processing practical work completed using **Python, OpenCV, NumPy, and Matplotlib** in Google Colab.

## Experiments

### Experiment 1 — Basic Image and Video Operations

* Read, display, and write an image
* Convert images into different formats such as PNG and TIFF
* Resize images
* Convert a colored image into grayscale
* Read and display a video
* Extract frames from a video

### Experiment 2 — Image Conversion

* Convert a grayscale image into a binary image

  * Using mean intensity as the threshold
  * Using a user-defined threshold
* Convert an RGB image into a grayscale image

  * Using the mean average of the R, G, and B planes
  * Using user-defined weightages for the R, G, and B planes

### Experiment 3 — Image Operations

* Add a border/padding around an image

  * Binary images
  * Grayscale images
  * User-defined border width and color
* Perform image complement

  * Binary images
  * Grayscale images

### Experiment 4 — Image Enhancement

* Log transformation
* Power-law/Gamma transformation
* Intensity-level slicing / contrast stretching

### Experiment 5 — Image Smoothing

* Smooth an input image using different spatial filters
* Apply averaging (un-weighted) filter
* Apply weighted filter using the given filter function
* Apply Gaussian filter
* Input the filter size from the user
* Input sigma for the Gaussian filter
* Apply different padding methods

  * Zero padding
  * Replication
  * Reflection
  * Reflection 101

### Experiment 6 — Histogram Processing

* Enhance the contrast of a grayscale image using histogram equalization
* Display the original and equalized images
* Display the histograms of the original and equalized images
* Perform histogram matching using a reference image
* Calculate histograms and cumulative distribution functions (CDF)
* Match the histogram of the input image with the reference image

### Experiment 7 — Image Sharpening

* Sharpen the input image using Laplacian filter
* Sharpen the input image using Sobel gradient operators
* Perform edge detection using Canny edge detector
* Perform image sharpening using unsharp masking
* Obtain the blurred image using Gaussian filter

  * Filter size: 5 × 5
  * Sigma: 3

## Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Google Colab

## Repository Structure

```text
Image-Video-Processing/
│
├── Experiment-1/
├── Experiment-2/
├── Experiment-3/
├── Experiment-4/
├── Experiment-5/
├── Experiment-6/
├── Experiment-7/
└── README.md
```
