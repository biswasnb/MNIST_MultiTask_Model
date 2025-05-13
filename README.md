# MNIST Multi-Task Model

This project builds a multi-task deep learning model using Keras to classify both:

- **Digits (0–9)** from the MNIST dataset  
- **Color Tint (Red or Green)** added artificially to the images

---

## Features

- Shared CNN layers with two output heads (digit & color)
- Custom data generator to apply red/green tint
- Trained using TensorFlow for 10 epochs
- TensorBoard support for training visualization
- Evaluation via visual prediction comparisons
