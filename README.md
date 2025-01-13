# Image PCA Compression and Reconstruction

This project demonstrates how to apply Principal Component Analysis (PCA) for dimensionality reduction on an image. It uses Python and the following libraries:
- `skimage` for image processing
- `matplotlib` for visualization
- `numpy` for numerical operations
- `sklearn` for PCA implementation

## Overview

The goal of this project is to reduce the dimensionality of an image using PCA and then reconstruct the image using a reduced set of principal components. This is commonly used in image compression techniques to reduce the storage size while retaining the most significant features of the image.

### Steps involved:
1. **Upload an image**: Upload the image from your local machine to the notebook.
2. **Preprocess the image**: Convert the image to grayscale if it is in RGB format.
3. **Standardize the image**: Flatten the image and normalize it.
4. **Apply PCA**: Reduce the dimensionality of the image using PCA.
5. **Reconstruct the image**: Reconstruct the image using the reduced components.
6. **Visualize the results**: Display the original and reconstructed images for comparison.

## Requirements

- Python 3.x
- Libraries: `numpy`, `matplotlib`, `skimage`, `sklearn`

You can install the required libraries using the following commands:
```bash
pip install numpy matplotlib scikit-image scikit-learn
