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

### Experiment 8 — Local Binary Pattern and Image Denoising

* Implement Local Binary Pattern (LBP) on a grayscale image
* Generate the LBP image
* Display the LBP image
* Plot the histogram of LBP values
* Add Gaussian noise to the input image
* Add speckle noise to the input image
* Denoise the noisy images using different filters
* Apply Wiener filter

  * 3 × 3 window
  * 5 × 5 window

* Apply median filter

  * 3 × 3 window
  * 5 × 5 window

* Apply Gaussian filter

  * 3 × 3 window
  * 5 × 5 window

* Apply bilateral filter

  * 3 × 3 window
  * 5 × 5 window

* Compare the denoising results

### Experiment 9 — Noise Generation Using Probability Distributions

* Generate different types of noise using probability distribution equations
* Generate Uniform noise
* Generate Gaussian noise
* Generate Erlang (Gamma) noise
* Generate Exponential noise
* Generate Rayleigh noise
* Compare the generated noise with built-in noise functions
* Plot histograms of the generated noise
* Analyze the shape of the noise distributions

### Experiment 10 — Adaptive Median Filtering and Otsu's Global Thresholding

* Add salt-and-pepper noise to the input image
* Implement an adaptive median filter
* Input the initial window size from the user
* Input the maximum window size (Smax) from the user
* Apply adaptive median filtering
* Apply standard median filtering
* Compare the performance of median and adaptive median filters
* Calculate PSNR values
* Read the input grayscale image
* Apply Otsu's global thresholding
* Automatically determine the optimal threshold value
* Segment the image into foreground and background
* Display the thresholded image
* Display the histogram with the selected threshold

## Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* SciPy
* Scikit-Image
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
├── Experiment-8/
├── Experiment-9/
├── Experiment-10/
└── README.md
```
