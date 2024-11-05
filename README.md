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
- `pip install opencv-python mediapipe pyautogui`

## Usage
1. Clone the repository
git clone https://github.com/your-username/eye-controlled-mouse.git  
cd eye-controlled-mouse  

2. Run the script  
python eye_controlled_mouse.py  

3. Position yourself in front of your webcam. The program will detect your face and begin tracking your eyes. Moving your gaze will move the mouse pointer, and a blink will simulate a click.  
