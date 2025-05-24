# Image Resizing 

## Overview
This project demonstrates various image resizing techniques using Python and OpenCV, including both upsampling and downsampling. The notebook provides visual and histogram-based comparisons of different interpolation methods.

## Table of Contents
- Introduction
- Choosing and Reading the Image
- Plotting the Image and Its Histogram
- Upsampling
  - Nearest Neighbor (from scratch)
  - Bilinear Interpolation
  - Lanczos Interpolation
  - Visual Comparison
- Downsampling
  - Gaussian
  - Bilinear
  - Bicubic
  - Visual Comparison
- Extra Visualizations
  - Gaussian Downsampling vs. Lanczos Upsampling (image and histogram)

## Main Steps
1. **Import Libraries**: Uses OpenCV, NumPy, and Matplotlib.
2. **Read and Display Image**: Loads an image and displays it with its histogram.
3. **Upsampling**:
   - Nearest Neighbor (custom implementation)
   - Bilinear (OpenCV)
   - Lanczos (OpenCV)
   - Visual comparison and saving results
4. **Downsampling**:
   - Gaussian (OpenCV)
   - Bilinear (OpenCV)
   - Bicubic (OpenCV)
   - Visual comparison and saving results
5. **Extra**:
   - Side-by-side comparison of Gaussian downsampling and Lanczos upsampling
   - Histogram comparison of the above

## Example Output
Example upsampling and downsampling results are saved as images in the project directory. You can also view the visualizations directly in the notebook.

## How to Run
1. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
2. Place your image as `IMG.jpg` in the project directory (or update the path in the notebook).
3. Open and run `Image Resizing.ipynb` in Jupyter or VS Code.

## Requirements
See `requirements.txt` for the full list. Main packages:
- opencv-python
- numpy
- matplotlib

## Project Structure
```
Image Resizing.ipynb
IMG.jpg
nearest_neighbor_upsampled_image.jpg
bilinear_upsampled_image.jpg
Lanczos_upsampled_image.jpg
gaussian_downsampled_image.jpg
bilinear_downsampled_image.jpg
bicubic_downsampled_image.jpg
README.md
requirements.txt
```

## Author
- Mostafa Eslam Elsayed
- Date: May 2025
