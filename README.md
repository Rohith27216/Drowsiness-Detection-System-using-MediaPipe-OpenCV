# 🚗😴 Drowsiness Detection System using MediaPipe & OpenCV

A real-time **Drowsiness Detection System** that monitors eye movements through a webcam and detects signs of fatigue using facial landmarks. When prolonged eye closure is detected, the system generates an alert to help improve driver safety.

## 📌 Project Overview

Driver drowsiness is one of the major causes of road accidents. This project uses **Computer Vision** techniques to detect whether a person is feeling drowsy by analyzing eye movements in real time.

The system captures live video from a webcam, detects facial landmarks using **MediaPipe**, extracts eye landmarks, calculates the **Eye Aspect Ratio (EAR)**, and triggers an alert if the eyes remain closed for a specific duration.

## 🔍 Project Workflow

```text
Webcam Input
      ↓
Face Detection using MediaPipe
      ↓
Eye Landmark Extraction
      ↓
Eye Aspect Ratio Calculation
      ↓
Drowsiness Detection
      ↓
Alert Generation
🛠️ Technologies Used
Python
OpenCV
MediaPipe
NumPy
VS Code
✨ Features
Real-time webcam-based detection
Face landmark detection using MediaPipe
Eye movement tracking
Eye Aspect Ratio calculation
Alert generation for prolonged eye closure
Lightweight and easy to run
📂 Project Structure
Drowsiness-Detection-System/
│
├── main.py
├── requirements.txt
├── README.md
└── assets/
    └── output_screenshot.png
