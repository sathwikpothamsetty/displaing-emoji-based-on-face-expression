# Display Emoji Based on Face Expression 😊
This project is a Python-based application that detects facial expressions in real time and displays corresponding emojis based on the identified emotion. It uses Haar Cascade Classifiers for face detection and an SVM (Support Vector Machine) classifier for expression recognition.

#🚀 Features
Real-time face detection using Haar Cascade.

Expression classification using SVM.

Displays relevant emoji based on detected emotion.

Simple and user-friendly interface.

#🛠️ Technologies Used

Python

OpenCV – for image processing and face detection.

Haar Cascade Classifier – for real-time face detection.

Scikit-learn (SVM Classifier) – for training and predicting facial expressions.

Tkinter / OpenCV  – for visual display.

#🧠 How It Works

Face Detection: The application uses OpenCV's Haar Cascade classifier to detect faces in the video stream.

Expression Classification: The detected face is passed to a pre-trained SVM classifier which predicts the emotion (e.g., happy, sad, angry, surprised).

Emoji Display: Based on the predicted emotion, the corresponding emoji is displayed on the screen.

#🧪 Getting Started

#Prerequisites

#Make sure you have the following installed:

Python 3.x

OpenCV

NumPy

Scikit-learn

Matplotlib (optional for visualization)
