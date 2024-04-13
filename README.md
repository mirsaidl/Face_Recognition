# Face Recognition

### Results
![alt text](<outputs/mirsaid.png>)
<video controls src="outputs/face_recog_roommates.mp4" title="FaceRecognition"></video>


### **Face Recognition with OpenCV and face_recognition**

Overview:
This project implements face recognition using OpenCV and the face_recognition library. It detects faces in a webcam feed, matches them against a set of known faces, and annotates the video feed with the names of the recognized individuals in real-time. The annotated video is then saved as output.avi.

Features:
Real-time Face Detection: The program captures frames from the webcam in real-time and detects faces using OpenCV.

Face Recognition: The detected faces are compared against a set of known faces. If a match is found, the name of the recognized person is displayed on the video.

Annotation: The program draws bounding boxes around the detected faces and annotates them with the names of recognized individuals.

Video Saving: The annotated video feed is saved as output.avi in the same directory. This allows users to review the face recognition results later.

Technologies Used:
OpenCV: OpenCV is used for capturing video from the webcam, image manipulation, and drawing annotations on the video frames.

face_recognition Library: The face_recognition library provides the face detection and recognition capabilities. It allows us to compare face encodings and determine if a detected face matches a known face.

Python: The project is implemented in Python, making use of its libraries and functionalities for face recognition and video processing.

How to Use:
Run the provided Python script in a compatible environment (such as Google Colab or a local Python environment with OpenCV and face_recognition installed).

The webcam feed will start, and the program will detect faces in the video stream.

If a known face is recognized, the program will annotate the video feed with the name of the recognized person.

The annotated video feed will be saved as output.avi in the same directory.

Press q to stop the program and close the webcam feed.

Applications:
Security Systems: This project can be used in security systems to recognize authorized personnel and raise alerts for unknown individuals.

Attendance Systems: It can also be used in automated attendance systems for schools or organizations, where the system recognizes students or employees as they enter a room.

Personal Projects: Individuals can use this project for fun applications like creating personalized videos with name annotations for family gatherings or events.

Future Enhancements:
Performance Optimization: Implement optimizations for faster face detection and recognition, such as multi-threading.

User Interface: Develop a graphical user interface (GUI) for easier interaction and control of the application.

Database Integration: Integrate with a database to store and manage known faces for larger-scale applications.

Deep Learning: Explore deep learning models for more accurate and robust face recognition.

Conclusion:
This face recognition project demonstrates the capabilities of OpenCV and face_recognition for real-time face detection and recognition. By leveraging these technologies, it provides a foundation for more advanced applications in security, attendance systems, and personal projects.
