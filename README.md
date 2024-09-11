Hand Gesture Recognition for Medicine Selection


This project implements a Hand Gesture Recognition System using OpenCV and Python. The system is designed for shopkeepers to minimize physical contact with customers during the COVID-19 pandemic. Customers can use hand gestures to select medicines numbered on a board, and the shopkeeper can identify the required medicine based on the recognized gestures. This ensures a contactless transaction while maintaining social distance.

Table of Contents
Introduction
Features
Technologies Used
Installation
Usage
Dataset
Results
Contributing
License


Introduction

In a post-COVID-19 world, maintaining social distance and reducing physical contact has become increasingly important. This project focuses on helping shopkeepers and pharmacists interact with customers without physical contact. The Hand Gesture Recognition System allows customers to use hand gestures to indicate the number corresponding to the medicine they need from a board, and the system detects the gesture and provides the input to the shopkeeper.

Features

Real-time hand gesture detection.
Recognizes numbers displayed through hand gestures.
Uses OpenCV for image processing and computer vision tasks.
Easy-to-use interface for selecting medicines based on gestures.
Efficient and fast recognition process for practical use in stores.
Technologies Used
Python: The programming language used for the implementation.
OpenCV: For real-time hand gesture detection and image processing.
NumPy: For matrix operations and numerical processing.
MediaPipe: For hand landmark detection (if used).
Machine Learning (optional): For custom gesture recognition algorithms.

Installation

Prerequisites
Python 3.x
Pip

Step-by-Step Guide

1.Clone the repository:

git clone https://github.com/yourusername/hand-gesture-recognition.git
cd hand-gesture-recognition
Install dependencies: Install the required libraries using the requirements.txt file:


pip install -r requirements.txt
Set up OpenCV: Make sure you have OpenCV installed:

pip install opencv-python
Run the application: Run the main script to start the hand gesture recognition:


python hand_gesture_recognition.py

Usage

The system will start the camera feed and process real-time hand gestures.
Ensure your hand is within the camera frame. Based on the number of fingers raised, the system will detect the corresponding number (e.g., 1 finger = Medicine 1, 2 fingers = Medicine 2, etc.).
The recognized number will be displayed on the screen.
Dataset
For training and testing, a custom dataset of hand gestures can be used. The system works with images or video sequences of hands in different positions representing numbers (1 to 5).

If you're using a custom dataset for machine learning:

Store images in a dataset folder.
Ensure labels match the hand gesture.
You can also use pre-trained models and datasets available through MediaPipe or other computer vision libraries.

Results

The system is able to:

Recognize gestures with high accuracy in good lighting conditions.
Handle different hand orientations to a reasonable extent.
Provide real-time feedback for practical use in a shop or pharmacy environment.
Example of Output:
Gesture Detected: 3
Corresponding Medicine: Paracetamol
Contributing
Contributions are welcome! If you'd like to improve this project, please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m 'Add new feature').
Push to your fork (git push origin feature-branch).
Open a pull request.





