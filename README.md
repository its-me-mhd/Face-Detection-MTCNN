# Face Detection MTCNN

This repository contains a Jupyter notebook that demonstrates a basic face detection and recognition pipeline using the MTCNN (Multi-task Cascaded Convolutional Networks) model. The notebook is designed to run on Google Colab, making it easy to use without requiring local setup.

## Overview

The project involves the following steps:

1. **Mounting Google Drive**: Accessing the dataset stored in Google Drive.
2. **Installing MTCNN**: Installing the MTCNN library using `pip`.
3. **Importing Libraries**: Importing necessary libraries like `cv2`, `os`, `numpy`, `tensorflow`, and `matplotlib`.
4. **Loading an Image**: Loading an image from Google Drive using OpenCV.
5. **Converting Image Color**: Converting the image from BGR to RGB format for display.
6. **Face Detection**: Using the MTCNN model to detect faces in the image and highlighting the detected face with a red rectangle.
7. **Displaying the Image**: Displaying the image with the detected face using `matplotlib`.

## Technologies Used

- **Python**: The primary programming language used for the project.
- **Google Colab**: Used for running the Jupyter notebook in the cloud.
- **Google Drive**: Used for storing and accessing the dataset.
- **OpenCV**: Used for image processing tasks.
- **MTCNN**: A deep learning model used for face detection.
- **TensorFlow**: Used as the backend for the MTCNN model.
- **Keras-FaceNet**: A pre-trained model for generating face embeddings.
- **scikit-learn**: Used for machine learning tasks such as clustering, classification, or evaluation metrics.
- **NumPy**: Used for numerical computations and array manipulations.
- **Matplotlib**: Used for displaying images.

## How It Works

1. **Setup**: The notebook starts by mounting Google Drive and installing the MTCNN library.
2. **Image Loading**: An image is loaded from Google Drive using OpenCV.
3. **Color Conversion**: The image is converted from BGR to RGB format for proper display.
4. **Face Detection**: The MTCNN model is used to detect faces in the image. The detected face is highlighted with a red rectangle.
5. **Display**: The image with the detected face is displayed using `matplotlib`.

## Requirements

- **Google Colab**: No local setup is required if using Colab.
- **Google Drive Account**: For storing and accessing the dataset.
- **Python Libraries**: The notebook will automatically install the required libraries (opencv-python, mtcnn, tensorflow, matplotlib) when run in Colab.
