# Sign Language Classification Project

This repository contains a project focused on recognizing and classifying sign language gestures using machine learning techniques. The project is implemented in Python and uses popular libraries such as TensorFlow, Keras, and OpenCV.

## Overview
This project is designed to address the challenge of recognizing sign language gestures, which is a critical step toward facilitating communication for individuals with hearing or speech impairments. The project leverages computer vision and deep learning to analyze hand gestures captured in images or real-time video streams. By training a convolutional neural network (CNN) on a dataset of labelled sign language gestures, the system can accurately identify and classify different signs. Additionally, the integration with OpenCV enables real-time gesture detection, making it a practical tool for real-world applications such as translation devices or assistive technologies.

## Features
- **Data Preprocessing:** Efficient image data handling for training and testing.
- **Model Training:** Utilizes convolutional neural networks (CNNs) for gesture classification.
- **Real-Time Detection:** Integration with OpenCV for real-time gesture recognition.

## Prerequisites
Before running the project, ensure you have the following installed:

- Python 3.8 or above
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook (optional for running the provided notebook)

## Dataset
The dataset used for this project contains labelled images of various sign language gestures. If you're using an external dataset, ensure it follows a similar structure for compatibility.

## Results
The model achieves high accuracy in classifying gestures. Detailed performance metrics, including confusion matrices and accuracy curves, are available in the notebook.
From the result, we can say that:

i) The unbiased accuracy estimate of a deep learning model is 96.1%

ii) The letter with the lowest individual accuracy is the letter "T"

iii) For the most common error we can say that the letter "T" is most commonly classified as "X"

## Recommendations:

For our dataset the letters "J" and "Z" are not included thus our model won't classify these two letters or else might miss-classify these which will not give accurate results for other datasets. Thus for further analysis, we can say that if provided by a better dataset it can give a better accuracy on any dataset

## Contribution
Contributions are welcome! If you'd like to improve this project or add new features, feel free to fork the repository and submit a pull request.

## Acknowledgments
- This project was part of my master's degree from The University of Adelaide.


