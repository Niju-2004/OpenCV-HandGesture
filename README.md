# OpenCV-HandGesture
 Hand Tracking, Gesture Recognition, Scroll Mode, Volume Control Mode, Cursor Movement Mode, Real-Time Feedback.

# Hand Tracking and Gesture Control

This Python script utilizes computer vision and hand tracking to enable gesture-based control of various system functionalities. It allows users to scroll, control volume, and move the mouse cursor using simple hand gestures.

## Features

- **Hand Tracking**: Detects and tracks hand landmarks in real-time using a webcam.
- **Gesture Recognition**: Recognizes specific hand gestures to trigger different modes of operation.
- **Scroll Mode**: Allows scrolling up or down using specific finger gestures.
- **Volume Control Mode**: Enables control of the system volume by adjusting the distance between the thumb and index finger.
- **Cursor Movement Mode**: Allows moving the mouse cursor based on the position of the index finger.
- **Real-Time Feedback**: Displays the current mode and relevant information (e.g., volume level, FPS) on the video feed.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI
- AutoPy
- PyCAW

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/hand-tracking-gesture-control.git
   cd hand-tracking-gesture-control
Install the required dependencies:

pip install opencv-python mediapipe pyautogui autopy pycaw
Usage
Ensure your webcam is connected and accessible.

Run the script:


python hand_tracking.py
Follow the on-screen instructions to use the gesture controls:

Scroll Mode: Raise your index finger to scroll up and both index and middle fingers to scroll down.
Volume Control Mode: Adjust the distance between your thumb and index finger to increase or decrease the system volume.
Cursor Movement Mode: Move your index finger to move the mouse cursor and lower your thumb to click.
Example Gestures
Scroll Up: Index finger raised.
Scroll Down: Index and middle fingers raised.
Volume Control: Adjust the distance between the thumb and index finger.
Cursor Movement: Move the index finger to move the cursor; lower the thumb to click.
Code Structure
HandDetector Class: Handles hand detection and landmark tracking using MediaPipe.
Volume Control: Uses the pycaw library to control the system volume.
Main Loop: Captures video frames, detects gestures, and performs actions based on the recognized gestures.
Contributing
Contributions are welcome! Please open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
MediaPipe for hand tracking.
PyAutoGUI for mouse and keyboard control.
AutoPy for mouse movement.
PyCAW for volume control.
