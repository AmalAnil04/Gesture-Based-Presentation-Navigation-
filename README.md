PowerPoint Gesture Control
A Python-based gesture control system for PowerPoint presentations using hand gestures and webcam input. This application allows you to control your PowerPoint presentations using natural hand gestures, making your presentations more interactive and engaging.

Features
Natural Hand Gestures: Control your presentation using intuitive hand movements
Laser Pointer Mode: Point to specific areas on your slides
Smooth Gesture Detection: Advanced gesture recognition with smoothing to prevent accidental triggers
Real-time Feedback: Visual feedback of detected gestures
Cross-platform Support: Works on macOS, Windows, and Linux
Gestures
Fist Gesture (👊)

Toggles the laser pointer mode
Uses Command+L keyboard shortcut
Pinch Gesture (🤏)

Toggles fullscreen mode
Uses Command+Enter keyboard shortcut
Swipe Left (👈)

Goes to the previous slide
Uses Left Arrow key
Swipe Right (👉)

Goes to the next slide
Uses Right Arrow key
Point Gesture (👆)

Activates laser pointer mode
Move your index finger to point at specific areas
Requirements
Python 3.7 or higher
OpenCV (cv2)
MediaPipe
NumPy
PyAutoGUI
Usage
Make sure your webcam is connected and working
Open your PowerPoint presentation
Run the gesture control system:
python gesture_control.py
Position yourself in front of the webcam
Use the gestures to control your presentation
Tips for Best Performance
Ensure good lighting conditions
Keep your hand within the webcam's view
Make clear, distinct gestures
For fist gesture, curl all fingers into your palm
For swipe gestures, move your hand horizontally with fingers extended
For pinch gesture, bring thumb and index finger close together
Troubleshooting
If gestures aren't being detected:

Check webcam permissions
Ensure proper lighting
Adjust your distance from the webcam
Make more distinct gestures
If laser pointer isn't working:

Ensure PowerPoint is in focus
Check if Command+L shortcut is enabled in PowerPoint
Try toggling the laser pointer mode again
Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
MediaPipe for hand tracking capabilities
OpenCV for computer vision support
PyAutoGUI for system control
