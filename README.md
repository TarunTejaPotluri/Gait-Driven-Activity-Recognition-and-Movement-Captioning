# Gait-Driven-Activity-Recognition-and-Movement-Captioning

activity-recognition/
│

├── app.py                   # Streamlit app to run the activity recognition

├── requirements.txt         # List of dependencies

├── README.md                # Project documentation

└── sample_data/

    └── v4.mp4               # Sample video file used in the project

This project demonstrates how to use Mediapipe and OpenCV to perform real-time activity recognition from a video file. The activities recognized include Walking, Clapping, Running, and detecting abnormal movements based on the angles between the shoulder, elbow, and wrist landmarks.

## Table of Contents
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Project Structure](#project-structure)
- [Streamlit App](#streamlit-app)
- [Acknowledgments](#acknowledgments)

## Installation

### Google Colab
To run this project in Google Colab, ensure that you have the following libraries installed:

```bash
!pip install mediapipe opencv-python
