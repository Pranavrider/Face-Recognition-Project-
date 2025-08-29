# 🧠 Face Recognition Project

A Python-based face recognition system that captures images, trains a model, and performs real-time facial recognition using OpenCV and dlib. Ideal for learning computer vision fundamentals or building a basic biometric authentication system.

---

## 📦 Features

- 📸 Capture face images from webcam
- 🧬 Train a face recognition model using encodings
- 🕵️‍♂️ Real-time face detection and recognition
- 🧪 Hardware integration support (optional)
- 🗂️ Dataset management and image renaming utilities

---

## 🛠️ Installation

Clone the repository and install dependencies:


git clone https://github.com/Pranavrider/Face-Recognition-Project-.git
cd Face-Recognition-Project-
pip install -r requirements.txt
python image_capture.py
python renamer.py
python facial_recognition.py
python model_training.py

## 🛠️Project Structure

├── dataset/                         # Captured face images
├── encodings.pickle                # Serialized face encodings
├── image_capture.py                # Webcam image capture script
├── renamer.py                      # Utility to rename images
├── model_training.py               # Train face recognition model
├── facial_recognition.py           # Real-time recognition script
├── facial_recognition_hardware.py  # Optional hardware integration
├── requirements.txt
├── README.md

Testing
Basic testing can be done by running each script and verifying output manually. Automated test scripts can be added for model accuracy and performance benchmarking.






