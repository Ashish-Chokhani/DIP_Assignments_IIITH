# Image Processing Assignment 1

## Directory Structure
 
  ```
  ├── src
        ├──  main.ipynb
  ├── src_img
  ├── out_img
  └── README.md
  ```
- `src` contains the Jupyter notebook used for the assignment.
- `src_img` folder contains images used for the questions.
- `out_img` folder contains output images of the question.


## Overview

The notebook `main.ipynb` contains the implementation of various image processing tasks. This includes quantization, histogram equalization, LSB decryption, and linear transformations. Each question has been tackled through detailed code implementations, visualizations, and explanations.

## Tasks

1. **Quantization of Images**:  
   Lenna's image was quantized to n (1-8) bits. The visual effects of quantization at different levels were demonstrated using a 2x4 grid of images with a short commentary on the effect of bit-depth reduction.

2. **Histogram Equalization**:  
   The task involved creating a custom `histequalize()` function and applying it to images A (chosen image) and B (image.jpeg). The results are displayed through various subplots:
   - Original images and histograms.
   - Equalized histograms of the individual RGB channels.
   - Combined effects of equalization and comparison of histograms.

3. **LSB Image Decryption**:  
   A cryptic image was decrypted from `6_mod.png`, revealing hidden information. Additional subtasks involved exploring the proportion and dimensions of the decrypted message. Functions for encrypting and decrypting LSB-based images were implemented and tested.

4. **Linear Piece-wise Transformation**:  
   Linear piece-wise transformations were applied to images A and B. These transformations were visualized through subplots, and analysis was performed to understand the effect of transformations on different RGB channels.

## Key Learnings

Through this assignment, various image processing techniques were applied and visualized. The effects of quantization, histogram equalization, and LSB decryption were analyzed. The importance of understanding how transformations impact RGB channels was also highlighted.

