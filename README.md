
# Hand Gesture Recognition using TensorFlow and OpenCV

This project implements hand gesture recognition using TensorFlow and OpenCV. It is designed to recognize various hand gestures using a machine learning model trained on image data. The application can be used for a variety of purposes, including human-computer interaction and assistive technologies.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Files](#model-files)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Introduction
Hand gesture recognition is a significant field in computer vision that aims to interpret human hand movements using machine learning algorithms. This project leverages TensorFlow for model training and OpenCV for real-time video processing.

## Features
- Real-time hand gesture recognition
- Customizable gesture classes
- Easy to train on new gestures
- Uses TensorFlow for deep learning
- Utilizes OpenCV for image processing

## Installation
To get started with this project, follow these steps:

### Prerequisites
- Python 3.x
- TensorFlow
- OpenCV
- NumPy

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/MohiniPjadhav/Hand_gesture_recognition_project.git
   cd Hand_gesture_recognition_project
   ```

2. Create a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

4. Download the dataset (if applicable) and place it in the appropriate directory.

## Usage
To run the hand gesture recognition application, use the following command:

```sh
python hand_gesture_detection.py
```

This will start the application and open a window displaying the video feed with real-time hand gesture recognition.

## Dataset
The dataset used for training the model consists of hand gesture images. You can use publicly available datasets or create your own dataset by capturing images of different hand gestures.

### Model Files
The `mp_hand_gesture` directory contains the following files:
- `variables/`: Directory containing the model variables.
- `keras_metadata.pb`: Metadata for the Keras model.
- `saved_model.pb`: The trained TensorFlow model.

This will train the model and save the trained model weights to a file.

## Results
Include some sample images or a video demonstrating the hand gesture recognition performance. You can also include a description of the model's accuracy and any challenges faced during development.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes. We welcome contributions of all kinds, including bug fixes, new features, and documentation improvements.


## Acknowledgements
- [TensorFlow](https://www.tensorflow.org/)
- [OpenCV](https://opencv.org/)
