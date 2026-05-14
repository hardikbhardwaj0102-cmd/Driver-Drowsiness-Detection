🚗 Driver Drowsiness Detection System

A real-time system that detects driver drowsiness using computer vision and deep learning. It monitors eye state through a webcam and triggers an alarm when signs of fatigue are detected, helping prevent road accidents.

📌 Features
Real-time face and eye detection using OpenCV
CNN-based eye state classification (Open/Closed)
Audio alarm when drowsiness is detected
Webcam live feed processing
Lightweight and easy to run
🛠️ Tech Stack
Python
OpenCV
TensorFlow / Keras
NumPy
playsound
⚙️ How It Works
Captures video from webcam
Detects face and eyes using Haar Cascades
CNN model predicts eye state (open/closed)
If eyes remain closed for a threshold time, alarm is triggered
