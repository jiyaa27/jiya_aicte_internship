Human Pose Estimation Using Machine Learning

Overview

This project implements Human Pose Estimation using MediaPipe, Streamlit, and Matplotlib. The application captures real-time video input, detects key body points (joints), and visualizes the pose estimation on a web-based UI.

Features

Real-time pose estimation using MediaPipe

Interactive UI built with Streamlit

Graphical visualization using Matplotlib

Webcam support for live pose tracking

Keypoint analysis for understanding body posture

Installation

Prerequisites

Ensure you have Python 3.7+ installed on your system.

Step 1: Clone the Repository

git clone https://github.com/your-username/human-pose-estimation.git
cd human-pose-estimation

Step 2: Install Dependencies

pip install -r requirements.txt

Step 3: Run the Application

streamlit run app.py

Dependencies

The following Python libraries are required:

mediapipe
opencv-python
streamlit
matplotlib
numpy

Usage

Run the Streamlit app: The UI will open in your browser.

Click "Start Camera" to begin real-time pose estimation.

View keypoint analysis and pose visualization.

Press 'q' to stop the video stream.

Project Structure

📂 human-pose-estimation
│── app.py              # Main Streamlit application
│── requirements.txt    # List of dependencies
│── README.md           # Project documentation

Future Enhancements

Integrate with Deep Learning models (e.g., OpenPose, PoseNet)

Add pose classification for activity recognition

Support pose tracking over time with data visualization

