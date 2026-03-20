# Satellite Image Enhancement: ESA Maspalomas Station Case

## Project Overview
This project focuses on **Digital Image Processing (DIP)** techniques applied to satellite imagery. The main objective is to reduce noise and enhance the quality of images captured by ESA (European Space Agency) telescopes, specifically from the Maspalomas station.

The notebook explores the balance between noise reduction (denoising) and the preservation of critical edge details in astronomical data.

## Technologies & Libraries
* **Language:** Python
* **Libraries:**
  * `OpenCV`: For advanced image filtering and manipulation.
  * `NumPy`: For matrix-based image processing.
  * `Matplotlib`: For visual analysis and comparison of results.

## Applied Techniques
1. **Noise Analysis:** Identification of common artifacts in satellite captures.
2. **Smoothing Filters:** Implementation of:
   - **Gaussian Blur:** To reduce high-frequency noise.
   - **Median Filtering:** Effective against 'salt and pepper' noise.
   - **Bilateral Filtering:** Used to smooth images while strictly preserving edges.
3. **Parameter Optimization:** Fine-tuning filter kernels to achieve the best Signal-to-Noise Ratio (SNR).

## Key Results
- Successful denoising of raw satellite captures without losing significant morphological information of the observed celestial bodies.
- Visual comparison of filtering techniques demonstrating the superiority of bilateral filters for astronomical edge preservation.

---
*Project developed as part of the Applied Data Science degree (UCM).*
