
- `src` contains the Jupyter notebook for implementing assignment tasks.
- `data` contains images and audio files referenced in the assignment.

## Overview

The notebook `main.ipynb` includes implementations of various image processing tasks such as Fourier transforms, frequency domain filtering, image restoration, and morphological operations. Each question is tackled with clear explanations, code, and visual results to showcase the application of each technique.

---

## Tasks

### 1. Fourier Transform Analysis

- **Task**: Developed `dft1` to compute the Discrete Fourier Transform (DFT) of a 1D array, analyzing the frequency spectrum of `1.wav`. Plotted frequency vs. magnitude.
- **2D-DFT and FFT**: Created `dft2` and `fft1`, `fft2` functions for computing 2D-DFT and FFT, respectively. Compared the efficiency of `dft1` and `fft1` on arrays of different lengths and plotted execution time vs. array length.
- **Application on Synthetic Signals**: Computed and visualized the 2D-DFT of various synthetic signals (`I = 0.5(1 + sin(x))`, etc.).
- **Observation**: Noted differences in computation time between DFT and FFT, highlighting FFT's efficiency on large data.

---

### 2. Inverse Fourier Transform and Signal Reconstruction

- **Reconstruction**: Used `ifft1` to reconstruct the frequency spectrum of `1.wav` and plotted the original and reconstructed signals.
- **2D Image Reconstruction**: Implemented `ifft2` to reconstruct `img1.jpg` from its Fourier spectrum, demonstrating effective reconstruction with minimal loss.
- **Experiment with Phase and Magnitude Spectra**: Manipulated phase and magnitude spectra of `ein.jpg`, observing effects on reconstructed images when combining different spectra.

---

### 3. Smudged Fingerprint Restoration

- **Task**: Enhanced the clarity of `fingerprint.png` using a combination of lowpass and highpass filters.
- **Approach**: Employed filters to remove smudges and improve detail, ensuring that key fingerprint features are visible for accurate attendance marking.

---

### 4. Low-Resolution Image Enhancement

- **Objective**: Enhanced resolution of `google.jpeg`, making the image clearer and sharper.
- **Methods**: Applied filters that helped recover finer details, effectively increasing the perceived resolution of the image.

---

### 5. Artifact Removal in Photographs

- **Task**: Restored `bird.png` and `cart.jpg` images by identifying and removing artifacts.
- **Techniques**: Used noise reduction and artifact removal filters to improve image quality, producing visually pleasing results without significant detail loss.

---

### 6. Automated Coin Counting

- **Goal**: Counted the number of coins in `coin.jpg` using morphological operations.
- **Approach**: Preprocessed with thresholding and morphological operations to isolate individual coins. Calculated the number of distinct regions to obtain the coin count.

---

### 7. Skeletonization of Human Structure

- **Task**: Applied skeletonization to `human.png` to highlight the skeletal structure, useful for studying anatomical efficiency and structure.
- **Method**: Used morphological thinning to reveal a minimal skeletal structure representation.

---

### 8. Fingerprint Cleaning and Edge Detection

- **Objective**: Cleaned `fingerprint2.png` to improve clarity for fingerprint recognition.
- **Approach**: Employed morphological operations, Gabor filters, and thresholding for noise reduction, enhancing key fingerprint features for better recognition.

---

## Conclusion

This assignment explored advanced image processing techniques, from Fourier transforms to morphological operations. Each task provided insights into real-world applications of digital image processing, with code, explanations, and visual comparisons in `main.ipynb`.
