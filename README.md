# Driver_Companion_Application
# Project Overview

The Driver Companion Application is designed to assist daily automobile drivers by offering features like Parking Assist and Drowsiness Detection. The app uses computer vision and machine learning techniques to enhance driving safety and convenience.

# Features

1. Parking Assist

Uses YOLO v4 (You Only Look Once) object detection model.

Calculates distance between the vehicle and nearby objects using camera calibration.

Displays distance alongside the live camera feed.

Emits a beep sound when the car is within 0.5 meters of an object.

2. Drowsiness Detection

Utilizes CNN (Convolutional Neural Networks) for eye detection.

Alerts the driver with a high-pitched beep if drowsiness is detected.

Works using the smartphone selfie camera.

# Tech Stack

Programming Language: Python

Libraries: OpenCV, TensorFlow/Keras, YOLO v4

Hardware Requirements:

Android or iOS smartphone

Parking camera-equipped car

Smartphone selfie camera

Phone speaker
