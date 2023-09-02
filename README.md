# Driver Fatigue Detection System

Driver Fatigue Detection System is an innovative project designed to detect driver drowsiness using machine learning. It utilizes computer vision and facial landmarks to monitor a driver's eyes and trigger an alert if signs of drowsiness are detected.

## Installation

Before running the Driver Fatigue Detection System, ensure you have the required dependencies installed:

1. **scipy**: Install using `pip install scipy`
2. **OpenCV**: Install using `pip install opencv-python`
3. **numpy**: Install using `pip install numpy`
4. **imutils**: Install using `pip install imutils`
5. **pyglet**: Install using `pip install pyglet`
6. **dlib**: Installation of dlib might require additional steps depending on your platform. You can refer to the official [dlib website](http://dlib.net/) for installation instructions.

## Usage

To use the Driver Fatigue Detection System, follow these steps:

1. Run the drowsiness detection script:

- python drowsiness-detection.py
- The script will start capturing video from your webcam and analyze it in real-time.

## How It Works

The Driver Fatigue Detection System uses a combination of computer vision and machine learning techniques to monitor driver drowsiness. Key features of the system include:

- Detection of facial landmarks using the dlib library.
- Calculation of the eye aspect ratio (EAR) to determine if the driver's eyes are closing.
- Continuous monitoring of EAR to detect drowsiness.
- Sounding an alarm when drowsiness is detected.

The script (`drowsiness-detection.py`) runs a loop that captures video frames, detects facial landmarks, calculates EAR, and triggers an alarm if drowsiness is detected. The system offers real-time monitoring for enhanced driver safety.

## Folder Architecture

- `68 face landmarks.dat`: A pre-trained facial landmark model used for facial feature detection.
- `README.md`: This documentation file.
- `_dlib_pybind11.cp310-win_amd64.pyd`: Dlib library dependency (may vary depending on the platform).
- `alarm.wav`: Sound file for the alarm.
- `drowsiness-detection.py`: The main Python script responsible for drowsiness detection. It uses computer vision techniques and machine learning to monitor driver fatigue.

The Driver Fatigue Detection System is a valuable tool for improving road safety by alerting drivers when they exhibit signs of drowsiness. It can be integrated into existing vehicle safety systems or used as a standalone application.

Feel free to customize and enhance this system to meet your specific requirements and applications.
