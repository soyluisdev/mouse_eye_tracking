<<<<<<< HEAD
# eyetrackingmouse
Eye-Controlled Mouse Using Mediapipe and OpenCV
=======
# Eye-Controlled Mouse Using Mediapipe and OpenCV

This project uses a webcam to capture video, track facial landmarks with [Mediapipe](https://mediapipe.dev/), and control the mouse pointer based on eye movements. The program tracks the user's gaze to move the mouse and simulates a click when the user blinks. This hands-free control setup can be useful for accessibility applications or experimentation.

## Features

- **Gaze Tracking**: Moves the mouse pointer based on eye position.
- **Blink Detection**: Simulates a click when the user blinks.
- **Real-time Processing**: Uses OpenCV for video capture and real-time face tracking.

## Requirements

- Python 3.12.4
- Libraries: 
  - `opencv-python`
  - `mediapipe`
  - `pyautogui`

You can install the required packages using:
```bash
pip install opencv-python mediapipe pyautogui
>>>>>>> 0e8bd42 (Basic functions of tracking and clicking added)
