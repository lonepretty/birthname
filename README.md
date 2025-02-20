Overview

This project is a Live Hand Gesture Tracking and Recognition system using Mediapipe and OpenCV. It captures hand gestures via a webcam, processes them using Mediapipe Hands, and classifies them into predefined custom gestures. The recognized gestures are then converted into text.

Features

Real-time Hand Detection using Mediapipe Hands

Gesture Classification for predefined custom gestures

Text Conversion for recognized gestures

User-friendly and efficient implementation

Requirements

Make sure you have the following installed:

Python 3.x

OpenCV (cv2)

Mediapipe

NumPy

Install dependencies using:

pip install opencv-python mediapipe numpy

How It Works

Captures real-time hand gestures using a webcam.

Uses Mediapipe Hands to detect hand landmarks.

Extracts key landmark points and maps them to a trained model.

Classifies the gesture based on predefined hand positions.

Displays the recognized gesture as text.

Usage

Run the script using:

python main.py
