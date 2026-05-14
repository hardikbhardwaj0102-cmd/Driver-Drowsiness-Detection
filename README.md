🚗 Driver Drowsiness Detection System

A real-time system that detects driver drowsiness using computer vision and deep learning. It monitors eye state through a webcam and triggers an alarm when signs of fatigue are detected, helping prevent road accidents.

📌 Features
* Real-time face and eye detection using OpenCV
* CNN-based eye state classification (Open/Closed)
* Audio alarm when drowsiness is detected
* Webcam live feed processing
* Lightweight and easy to run

🛠️ Tech Stack

* Python
* OpenCV
* TensorFlow / Keras
* NumPy
* playsound

⚙️ How It Works

* Captures video from webcam
* Detects face and eyes using Haar Cascades
* CNN model predicts eye state (open/closed)
* If eyes remain closed for a threshold time, alarm is triggered

⚠️ Future Improvements

* Improve accuracy with better CNN model
* Add yawning detection
* Mobile app integration
* Night-time detection support

🧠 Goal

* To reduce road accidents by alerting drivers when they show signs of fatigue.

📂 Driver-Drowsiness-Detection

  ├── train/
        ├── closed/
        ├── open/
  ├── drowsiness.ipynb/
  ├── drowsiness_model.h5/
  ├── requirements.txt/
  ├── alarm.mp3/
  └── README.md/
