
# Viola_Jones_Face_Detection

Real-time face detection using the Viola–Jones algorithm with Haar cascade classifiers implemented in OpenCV.


👤 Real-Time Face Detection using Viola–Jones Algorithm

This project demonstrates real-time face detection using the Viola–Jones algorithm, implemented with Haar cascade classifiers in OpenCV. The algorithm efficiently detects frontal human faces and is widely used in surveillance, biometrics, and real-time recognition systems.

🎯 Objective


To apply the Viola–Jones object detection framework to detect human faces from static images and real-time webcam input using OpenCV’s built-in Haar cascades.

🛠️ What is Viola–Jones?

The Viola–Jones algorithm is a robust, real-time object detection technique that combines:

Haar-like features for capturing facial patterns

Integral Image for rapid feature computation

AdaBoost for selecting the most relevant features

Cascade Classifier for fast and efficient multi-stage detection

✅ It’s fast, lightweight, and works even on low-compute devices.




✅ Key Features

Two separate implementations:


📸 face_detection_image.py → Detects faces in static images

🎥 face_detection_video.py → Detects faces in live webcam/video feed


Real-time detection with bounding box annotations

Adjustable detection parameters like scaleFactor and minNeighbors


📂 Features Implemented

✅ Face Detection in:

Static images

Live webcam feed


✅ Controls and Features:

Draws bounding boxes around detected faces

Adjustable scale factor and minNeighbors for fine-tuning detection sensitivity


📁 Dataset / Classifier

Uses OpenCV pre-trained Haar cascade:

haarcascade_frontalface_default.xml



Optional: Eye/Smile detection using:

haarcascade_eye.xml

haarcascade_smile.xml


💻 Technologies Used

Python

OpenCV

NumPy

Webcam (for real-time input)

📈 Sample Output

Detected faces highlighted with rectangles in real-time.


Detection remains robust across varying lighting and orientations (frontal).


🔬 Additional Notes

While Viola–Jones is fast, it struggles with:


