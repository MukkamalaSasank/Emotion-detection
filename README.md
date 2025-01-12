Facial Emotion Recognition

This project demonstrates real-time facial emotion recognition using a deep learning model.

Key Features:

Model: A Convolutional Neural Network (CNN) is trained to classify facial expressions.

Dataset: Utilizes the FER 2013 dataset for training and evaluation.

Real-time Analysis: Processes live video from a webcam to detect and classify emotions.

How it works:

1. Training: The CNN model is trained on the FER 2013 dataset to accurately classify facial expressions into seven categories: anger, disgust, fear, happy, neutral, sad, and surprise.

2. Face Detection: During real-time operation, the system uses a face detector to locate faces within the video frames.

3. Emotion Prediction: For each detected face, the model analyzes the facial features and predicts the most probable emotion.

4. Visualization: The detected faces are displayed with corresponding emotion labels on the video stream.


To Run:

1. Install Dependencies:
    Install required libraries using pip install -r requirements.txt

2. Train Model (Optional):
    If you want to train a new model:
        Download and organize the FER 2013 dataset.
        Execute the train.py script to train the CNN model.
        The trained model weights will be saved as model_weights.h5

3. Run Recognition:
    Execute the test.py script to start real-time emotion detection from the webcam.
    The test.py script will automatically load the saved model_weights.h5 if available.


Dependencies:

Refer to requirements.txt for the list of necessary libraries.


Dependencies:

TensorFlow
Keras
OpenCV-Python
NumPy

Source: Kaggle: https://www.kaggle.com/datasets/msambare/fer2013