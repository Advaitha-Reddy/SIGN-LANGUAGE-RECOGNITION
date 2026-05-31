# Talk With Your Hands

A real-time Sign Language to Text and Speech Conversion System that recognizes American Sign Language (ASL) hand gestures using Computer Vision and Deep Learning. The system converts recognized hand signs into text  helping bridge communication gaps for hearing- and speech-impaired individuals.

## Overview

This project uses OpenCV, MediaPipe, and a Convolutional Neural Network (CNN) to detect hand gestures from a webcam feed and translate them into English text in real time.

The system focuses on recognizing ASL alphabet gestures (A-Z) and provides an interactive interface for building words and sentences.

## Features

- Real-time hand gesture detection using webcam
- ASL alphabet (A-Z) recognition
- CNN-based gesture classification
- Text generation from recognized signs
- Interactive GUI built with Tkinter
- Dataset collection utility for model training

## Tech Stack

- Python
- OpenCV
- MediaPipe
- TensorFlow / Keras
- NumPy
- Tkinter
  
## Modules

### 1. Data Collection

Files:
- `data_collection_binary.py`
- `data_collection_final.py`

Functions:
- Captures webcam input
- Detects hand landmarks
- Generates hand skeleton images
- Stores labeled images for training

### 2. Gesture Prediction

File:
- `prediction_wo_gui.py`

Functions:
- Loads trained CNN model
- Processes live webcam feed
- Predicts ASL alphabet gestures
- Displays recognized characters

### 3. GUI Application

File:
- `final_pred.py`

Functions:
- Real-time gesture recognition
- Sentence generation
- Word suggestions
- Interactive graphical interface

## Output
<img width="751" height="425" alt="Demo" src="https://github.com/user-attachments/assets/698fd326-a244-4c1a-9417-b60575d3d972" />

