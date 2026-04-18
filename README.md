# PowerPoint Gesture Control

A Python-based gesture control system for PowerPoint presentations using hand gestures and webcam input. This application allows you to control your PowerPoint presentations using natural hand gestures, making your presentations more interactive and engaging.

## Features

- **Natural Hand Gestures**: Control your presentation using intuitive hand movements
- **Laser Pointer Mode**: Point to specific areas on your slides
- **Smooth Gesture Detection**: Advanced gesture recognition with smoothing to prevent accidental triggers
- **Real-time Feedback**: Visual feedback of detected gestures
- **Cross-platform Support**: Works on macOS, Windows, and Linux

## Gestures

1. **Fist Gesture** (👊)
   - Toggles the laser pointer mode
   - Uses Command+L keyboard shortcut

2. **Pinch Gesture** (🤏)
   - Toggles fullscreen mode
   - Uses Command+Enter keyboard shortcut

3. **Swipe Left** (👈)
   - Goes to the previous slide
   - Uses Left Arrow key

4. **Swipe Right** (👉)
   - Goes to the next slide
   - Uses Right Arrow key

5. **Point Gesture** (👆)
   - Activates laser pointer mode
   - Move your index finger to point at specific areas

## Requirements

- Python 3.7 or higher
- OpenCV (cv2)
- MediaPipe
- NumPy
- PyAutoGUI

## Usage

1. Make sure your webcam is connected and working
2. Open your PowerPoint presentation
3. Run the gesture control system:
```bash
python gesture_control.py
