# Face_Detection_Smart-Home-Security-with-e-mail-alert-

Overview:
--------
This project implements a smart home security system using face detection technology. The system uses OpenCV and a trained model to recognize the faces of authorized users and send alerts when an unknown person is detected. It provides an enhanced layer of security by automatically identifying household members and alerting the homeowner in case of potential intruders.

Features:
--------
Real-time Face Detection: Utilizes OpenCV to capture live video feed and detect faces in real-time.

User Recognition: The system is trained to recognize specific individuals (e.g., "User 1") and classify others as "Unknown".

Email Alerts: Sends an email notification with a snapshot of the detected face when an unknown person is detected, enhancing security and allowing for quick response.

Scalable: Easily expandable to include multiple users, each with a unique face profile.

Technology Stack:
----------------
OpenCV: For image and video processing, face detection, and face recognition.

Python: The core programming language used to develop the project.

SMTP (Simple Mail Transfer Protocol): Used to send email alerts when an unknown face is detected.

Pre-trained Models: Utilizes face recognition models pre-trained on a dataset to ensure accurate detection and recognition.

How It Works:
--------------
Capture and Process Video: The system captures video from a webcam and processes each frame to detect faces.
Face Recognition: Detected faces are compared against a database of known faces. If a match is found, the system identifies the individual; otherwise, the face is marked as "Unknown".
Alert System: If an unknown face is detected, an email alert is sent to the homeowner with an attached image of the person.

Setup and Usage
---------------
Prerequisites
   Python 3.x
   OpenCV
   face_recognition
   smtplib (for email alerts)
   
Contributions are welcome! Please feel free to submit a Pull Request or raise an Issue for any improvements or bug fixes.
