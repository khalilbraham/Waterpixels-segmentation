# Waterpixels Segmentation Project

## Overview

The Waterpixels Segmentation project aims to implement the Waterpixels method for obtaining superpixels by leveraging the watershed algorithm controlled by markers. This method is designed to offer a linear complexity solution, providing an effective balance between boundary compliance and regularity.

## Reference

For an in-depth understanding of the Waterpixels method, please refer to the reference article: [Waterpixels: Superpixels based on the Watershed Transform](https://hal.archives-ouvertes.fr/hal-01212760).

## Project Structure

### 1. Introduction to Waterpixels
- **Description**: This section provides an overview of the Waterpixels method, its importance, and its applications in image processing.
- **Key Features**:
  - Linear complexity
  - Good boundary compliance
  - High regularity in superpixel generation

### 2. Implementation Details
- **Description**: Detailed explanation of the implementation steps for the Waterpixels method.
- **Steps**:
  1. **Preprocessing**: Preparing the image data for segmentation.
  2. **Marker Selection**: Choosing markers to control the watershed segmentation.
  3. **Watershed Algorithm**: Applying the watershed algorithm to generate superpixels.
  4. **Post-processing**: Refining the segmented superpixels for better accuracy.

### 3. Usage Instructions
- **Description**: Step-by-step guide to running the Waterpixels Segmentation algorithm.
- **Requirements**:
  - Python 3.x
  - OpenCV
  - NumPy
  - Matplotlib

#### Installation
```bash
pip install opencv-python numpy matplotlib
```

![Capture](https://github.com/souheib1/Waterpixels-Segmentation/assets/73786465/33151e86-4705-4d83-90d6-139b0f9ba875)

### **Reference article:** https://hal.archives-ouvertes.fr/hal-01212760 

