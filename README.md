# driver-drowsiness-detection-
Driver Drowsiness Detection App
A real‑time computer vision project that detects driver drowsiness using OpenCV, dlib, and facial landmarks. The system monitors eye blinks and classifies states as Active, Drowsy, or Sleeping, displaying alerts on the video feed.

 Features
- Real‑time webcam feed monitoring
- Facial landmark detection with dlib
- Blink ratio calculation for drowsiness detection
- Visual alerts: Active :), Drowsy !, SLEEPING !!!
- Extensible for sound alarms or logging events

 Requirements
- Python 3.12
- OpenCV (opencv-python)
- dlib
- imutils
- numpy
- face_recognition
You also need the shape_predictor_68_face_landmarks.dat model file (download from dlib.net and extract).

 Installation
Clone the repository:
git clone https://github.com/yourusername/driver-drowsiness.git
cd driver-drowsiness


Install dependencies:
py -3.12 -m pip install -r requirements.txt

active.png 
<img width="1920" height="1080" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/152daaf9-e7eb-471a-b630-1e0aa10dd0a5" />
sleeping.png 
<img width="1920" height="1080" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/9ab21e29-59e1-48c7-99ba-bac45f1fd647" />
drowsy.png
<img width="1920" height="1080" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/f2e6faa9-9123-4d06-a37e-c53210c467cb" />

Usage
Place shape_predictor_68_face_landmarks.dat in the project folder, then run:
py drowsiness_app.py


Press Esc to stop the program.

 Demo
The system detects three states in real time:
- Active :) (green)
- Drowsy ! (red)
- SLEEPING !!! (blue)

 Future Improvements
- Add sound alerts (beep/alarm) when drowsiness is detected
- Log events with timestamps for analysis
- Integrate with car systems for real‑world deployment


