# image-recognition-teachable-machine
Image classification model using Google Teachable Machine

## Overview
This project uses Google Teachable Machine to train an image classification model that distinguishes between two classes:
- Clear Path
- Obstacle

The trained model is exported in TensorFlow Keras format and used in a Python script to classify input images.

## Project Objectives
- Train an image recognition model using Google Teachable Machine.
- Export the trained model in TensorFlow Keras format.
- Load the model using Python.
- Predict the class of an input image.
- Display the predicted class and confidence score.

## Tools & Technologies
- Google Teachable Machine
- TensorFlow / Keras
- Python
- NumPy
- Pillow
- Google Colab

## Project Files
```
keras_model.h5      # Trained model
labels.txt          # Class labels
predict.py          # Python prediction script
README.md           # Project documentation
```

## How to Run
1. Download the project files.
2. Install the required libraries:
```
pip install tensorflow pillow numpy
```
3. Run the Python script.
4. Provide an input image.
5. The program will display the predicted class and confidence score.

## Example Output
```
Class: Clear Path
Confidence Score: 0.95
```

## Author
Aisha Alhuraysi
IT Graduate | Cybersecurity Track
