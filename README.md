# Air_Canva
This Python application allows you to paint on the screen using hand gestures detected via webcam. It uses the mediapipe library to detect hand landmarks and OpenCV for drawing and capturing frames from the webcam.

Features
Multiple Color Selection: Choose between blue, green, red, and yellow colors for drawing.
Clear Canvas: Clear the canvas by selecting the "CLEAR" button.
Real-time Drawing: Lines are drawn on both a live video feed and a separate canvas window.
Dynamic Brush Size: The size of the drawing brush dynamically changes based on finger distance.

Libraries Used
cv2 (OpenCV): For capturing video, image processing, and drawing functions.
numpy: For numerical operations on arrays.
mediapipe: For hand tracking and landmark detection.
collections: Used for managing color points with deque.

Usage
Run the script and point your webcam towards a clear background.
Raise your hand within the camera frame to start painting.
Use your index finger to draw on the screen:
Move your finger to draw lines.
Move it close to the top of the screen to select colors or clear the canvas.
Controls
Blue: Draw with blue color.
Green: Draw with green color.
Red: Draw with red color.
Yellow: Draw with yellow color.
CLEAR: Clears the canvas.

Notes
Ensure proper lighting and a clear background for optimal hand detection.
Adjust min_detection_confidence in the hands initialization for different confidence thresholds.
