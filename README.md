Smart Cradle Baby Monitoring System
A real-time AI-driven monitoring system designed to detect a baby's emotional state and provide live updates to parents via a cloud-based web dashboard.

🚀 Overview
This system uses a Convolutional Neural Network (CNN) to analyze facial expressions in real-time using a webcam. It classifies the baby's state into three categories: Normal, Sad, or Abnormal. The status is synced in real-time to a Firebase Realtime Database, which then updates a hosted web dashboard.

🛠️ Tech Stack
AI/ML: Python, TensorFlow, Keras, OpenCV.

Backend/Database: Firebase Realtime Database.

Frontend: HTML/JS, GitHub Pages (Hosting).

Development: VS Code, Git.

📋 Features
Real-time Emotion Detection: Identifies emotions using a trained CNN model.

Cloud Syncing: Automatically updates the status to the cloud only when a state change is detected (optimizing bandwidth).

Visual Feedback: Web dashboard displays the current status and confidence levels.

User Alerts: Easy-to-read UI with color-coded status indicators.

⚙️ Setup & Installation
1. Prerequisites
Ensure you have the following installed:

Python 3.x

Pip (Python Package Manager)

Webcam access
