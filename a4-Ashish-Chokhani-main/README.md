# Digital Image Processing - Assignment 4

- `src` contains the Jupyter notebook for implementing assignment tasks.
- `data` contains images referenced in the assignment.

## Overview

This assignment focuses on advanced image processing techniques, including segmentation, Hough Transform, and Harris Corner Detection. Implementations will be performed using Python and OpenCV, emphasizing practical application and clear visualization.

---

## Tasks

### 1. Image Segmentation Using Thresholding 
- **Objective**: Segment a grayscale image using thresholding methods.
- **Subtasks**:
  - Apply the following methods:
    - Binary Thresholding
    - Adaptive Thresholding
    - Otsu’s Thresholding (10 Marks)
  - Display the original and segmented images side by side for comparison with clear labels. (5 Marks)
  - Discuss which method provided the best segmentation and why, considering factors like object boundaries and noise. (5 Marks)

---

### 2. Line Detection Using Hough Transform 
- **Objective**: Detect and highlight straight lines in an image.
- **Subtasks**:
  - Use Canny edge detection and apply the Hough Line Transform to identify straight lines. (10 Marks)
  - Test the function on an image with distinct lines, such as roads or grid structures. Display the original and processed images. (5 Marks)
  - Experiment with threshold parameters, describe changes, and their effects on line detection. (5 Marks)

---

### 3. Circle Detection Using Hough Circle Transform
- **Objective**: Detect circular objects in an image.
- **Subtasks**:
  - Implement the Hough Circle Transform with preprocessing steps like smoothing for better accuracy. (10 Marks)
  - Apply the function to images with circular objects, displaying original and processed images. (5 Marks)
  - Experiment with radius ranges and accumulator thresholds. Explain observed improvements. (5 Marks)

---

### 4. Harris Corner Detection 
- **Objective**: Detect and mark corners in an image.
- **Subtasks**:
  - Create a function using the Harris Corner Detection method and overlay detected corners on the original image. (10 Marks)
  - Test on images with distinct corners, such as chessboards or buildings, and display results. (5 Marks)
  - Vary the sensitivity parameter `k`, observe effects, and explain findings. (5 Marks)

---

### 5. Short Theory 
- **Task**: Explain differences between the Hough Transform for line and circle detection in 100-150 words.
- **Considerations**:
  - Parameter space representation.
  - Computational complexity variations.

---

