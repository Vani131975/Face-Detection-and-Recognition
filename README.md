# Real-Time Face Detection and Recognition using DeepFace and OpenCV

This project performs real-time face recognition using a webcam. It uses the DeepFace library with the ArcFace model to compare a live video feed against a known image and label recognized faces.

### Overview

- Captures video from the webcam using OpenCV
- Detects faces using Haar Cascade classifiers
- Compares detected faces with a reference image using DeepFace's verify() method
- Displays bounding boxes and identity labels ("vani" or "Unknown") in real-time

### Technologies Used

- Python
- OpenCV
- DeepFace (ArcFace model)
- Haar Cascades for face detection

### Setup Instructions

Install dependencies

pip install deepface opencv-python

Replace the path to your known image in the script

Update the variable known_image_path with the path to your reference image.

Run the application

python main.py

Ensure the reference image is clear and front-facing.

The ArcFace model provides strong performance for face verification

Exit - Press the q key to stop the video stream and close the application
