# DeepFake Detection with MesoNet (Meso4)

## Overview

This project uses a pretrained **Meso4 model** to detect whether an input face image is real or a DeepFake. The model loads images, makes predictions, and categorizes results as correct or misclassified.
---

## Key Technologies

- Python 3.9.6
- TensorFlow 2.19.0
- NumPy
- OpenCV
- Matplotlib
- Keras
---

## Objectives

- Detect DeepFake images using a pretrained MesoNet (Meso4) model.
- Load and test a batch of face images from real and fake folders.
- Predict likelihood and visualize classification accuracy.
---

##  How to Use (Directory Setup)
Make sure you have the correct folder structure and that the pretrained weights are saved as `.weights.h5` files in the correct path. Change file path to file directory of where the weights and data files are stored.
