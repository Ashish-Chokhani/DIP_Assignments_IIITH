# Image Processing Assignment 2

## Directory Structure
 
  ```
  ├── src
        ├──  main.ipynb
  ├── data
  └── README.md
  ```
- `src` contains the Jupyter notebook used for the assignment.
- `data` folder contains images used for the questions.


## Overview

The notebook `main.ipynb` contains the implementation of various image processing tasks. This includes quantization, histogram equalization, LSB decryption, and linear transformations. Each question has been tackled through detailed code implementations, visualizations, and explanations.

## Tasks

### 1. Let’s Get Blurry 
- **Task**: Implemented 2D convolution (`conv2D`), Mean Filter, and Median Filter.
- **Results**: Applied filters on `IMG1` and plotted the time taken for different kernel sizes (k=3, 5, 7) across image dimensions (256x256, 512x512, 1024x1024).
- **Efficiency**: Developed an optimized `fastMeanFilter()` and compared its performance with the standard `meanFilter()`. Observed significant improvement in execution time with larger kernels.

---

### 2. Distribution is the Solution 
- **Gaussian Filter**: Applied Gaussian Filter (`gaussFilter`) on `IMG2` for different values of σ. Found the optimal σ for kernel size k=7, and plotted the result to verify.
- **Bilateral Filter**: Implemented Bilateral Filter (`bilaterFilter()`) and tested its performance for varying σs and σr. Commented on the difference between Gaussian and Bilateral filters.

---

### 3. Edge of Glory 
- **Sobel, Prewitt, Roberts Filters**: Applied Sobel, Prewitt, and Roberts operators on `IMG3`. Generated X-gradient, Y-gradient, and Edge Map for each filter.
- **Laplacian Filter**: Explored the effects of varying kernel sizes on the Laplacian filter.

---

### 4. Sharpen Up 
- **Unsharp Masking**: Applied `unsharpMask()` on `IMG4` and adjusted kernel size and σ for different sharpness levels.
- **Highboost Filtering**: Implemented `highboostFilter()` and compared results with Unsharp Masking for various boost factors (A=1.2, 1.5, 2.0). Highboost provided better fine-detail enhancement.

---

### 5. Rain Rain Go Away!
- **Task**: Removed rain from `IMG5` using Mean, Median, Gaussian, and Bilateral filters.
- **Best Method**: Bilateral filter produced the best result, as it preserved edges while smoothing out the rain noise.
- **Noise Identification**: Identified salt-and-pepper noise in `IMG6` and removed it effectively using a Median Filter.

---

### 6. Transform and Conquer
- **Coin Segmentation**: Developed a pipeline to segment overlapping coins in `IMG7` using morphological operations. Successfully separated each coin, similar to the target image.
- **Signature Skeletonization**: Skeletonized authentic and fraudulent signatures from the CEDAR dataset, observing stability in signature features.

---

### 7. Body Scan Enhancement 
- **Task**: Enhanced skeletal details in `IMG8` using sharpening filters. Applied multiple methods to emphasize bone structures in the image.

---

### 8. You Can’t See Me 
- **Task**: Cleaned the corrupted image `IMG9` using a combination of Mean, Median, and Gaussian filters. Achieved significant noise reduction with Median filtering.

---

## Conclusion
The assignment covered various image processing techniques, including convolution, filtering, edge detection, and morphological operations. The tasks were successfully implemented, with observations documented for each experiment in the notebook itself.

