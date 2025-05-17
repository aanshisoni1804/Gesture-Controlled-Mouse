# Virtual Mouse Using Hand Gestures

This project turns your hand into a virtual mouse. By detecting your hand via webcam and tracking finger movements, it lets you move the mouse cursor and perform clicks without touching the actual mouse. It enhances accessibility and offers an alternative human-computer interaction method.

## How It Works

- The webcam captures real-time video using OpenCV.
- MediaPipe identifies hand landmarks and tracks them frame-by-frame.
- The tip of the index finger (landmark 8) is used to control the mouse cursor position.
- If the index finger and middle finger (landmark 12) come close together, it triggers a mouse click using PyAutoGUI.
- The screen coordinates are mapped proportionally to the hand coordinates for smooth control.

## Technologies Used

- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- Numpy (for coordinate mapping and smoothing)

## Learning Outcomes

- Implementing hand tracking for practical applications
- Creating gesture-based UI systems
- Mapping image space to screen space
- Real-time control and optimization using computer vision

