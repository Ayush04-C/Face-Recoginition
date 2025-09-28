# Face Recognition Attendance System

A real-time attendance system using face recognition and OpenCV, which automatically logs attendance when a recognized face is detected via a webcam.

This project is designed for classrooms, workplaces, or any scenario requiring automated attendance tracking.

# Features

Real-time face detection and recognition using a webcam.

Automatic attendance logging in Attendence.csv with timestamps.

Supports multiple known faces loaded from an Images folder.

Visual feedback: displays bounding boxes and names on recognized faces.

# Tech Stack

Python 3.x

OpenCV (cv2) – for webcam access, image processing, and drawing bounding boxes.

face_recognition – for face encoding, detection, and recognition.

NumPy – for numerical operations like calculating face distances.


# Installation

1. Clone the repository:

	git clone https://github.com/YOUR-USERNAME/Face-Recognition-Attendance.git
	cd Face-Recognition-Attendance


2. Install dependencies:

	pip install opencv-python
	pip install face_recognition
	pip install numpy


Optionally, create a requirements.txt and run:

pip install -r requirements.txt


3. Add known faces:

	Place images of known people inside the Images folder.
  
	The file name (without extension) will be used as the person’s name in attendance.
  
	OS – to access and manage files in the Images folder.
  
	datetime – for recording timestamps in the attendance CSV file.
