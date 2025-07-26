# Basic Image Processing with OpenCV

## Overview

This project demonstrates fundamental image processing techniques using OpenCV. It covers essential tasks such as image loading, grayscale conversion, resizing with aspect ratio, Gaussian blurring, edge detection, drawing shapes, and gray level slicing.

The goal is to practice core OpenCV functions and understand how each image transformation affects the visual output.

---

## Features Implemented

1. **Image Loading**  
   Load an input image (`Assignment_Image.jpeg`) using OpenCV.

2. **Grayscale Conversion**  
   Convert the loaded color image to grayscale.

3. **Aspect Ratio Resizing**  
   Resize the image while preserving the original aspect ratio.

4. **Gaussian Blurring**  
   Apply Gaussian blur with kernel sizes:
   - (3, 3)
   - (5, 5)
   - (7, 7)

5. **Edge Detection**  
   Use the Canny edge detector with varying threshold values to observe changes in edge sensitivity.

6. **Drawing Shapes**
   - Draw multiple red rectangles with varying thickness.
   - Draw green circles with different radii.

7. **Gray Level Slicing**
   - Slicing with background preservation.
   - Slicing without background preservation.

8. **Saving Output**
   All intermediate and final images are saved locally with descriptive filenames.

---

## Technologies Used

- Python
- OpenCV (cv2)
- NumPy (for slicing logic)
