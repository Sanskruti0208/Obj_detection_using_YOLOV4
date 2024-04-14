# Obj_detection_using_YOLOV4

#Description
Smart-Object-Analyzer is a Python application that performs real-time object detection using OpenCV, Python, and YOLO (You Only Look Once) technology. The application utilizes the powerful capabilities of YOLO for detecting and recognizing objects within images or video streams.

#Features
Real-Time Object Detection: Utilizes YOLO pre-trained models for real-time object detection in images or video streams.
User Interface with Tkinter: Provides a user-friendly interface using Tkinter for easy interaction and control of the object detection process.
Interactive Object Detection: Allows users to click on a specific region of the frame to initiate object detection within that region.
Audio Feedback: Provides audio feedback using pyttsx3 to announce the detection of objects in the frame.
Data Logging: Logs detected objects and timestamps to a CSV file for further analysis and tracking.

#Usage
Clone the repository to your local machine.
Install the necessary dependencies:
Download the YOLOv4-tiny model weights and configuration files and place them in the dnn_model/ directory.
Run the main.py script to start the Smart-Object-Analyzer application.
Click on the green region in the video feed to detect objects within that region.
Detected objects will be announced through audio feedback, and their details will be logged to the detected_objects.csv file.

#Requirements
Python 3
OpenCV
pyttsx3

#Contributing
Contributions to the project are welcome! If you have any suggestions, bug fixes, or feature enhancements, feel free to open an issue or submit a pull request.

#License
This project is licensed under the MIT License. See the LICENSE file for more details.

#Acknowledgments
This project builds upon the work of the OpenCV, Python, and YOLO communities, whose contributions have made advanced object detection accessible to developers worldwide.
Special thanks to the developers of Tkinter and pyttsx3 for providing user interface and audio feedback capabilities.
