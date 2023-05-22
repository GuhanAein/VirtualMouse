Virtual Mouse using Hand Gestures

This project utilizes computer vision and hand gesture recognition to create a virtual mouse that can be controlled by hand movements. The application captures video from the webcam, detects the user's hand using the MediaPipe library, and maps the hand landmarks to control the mouse cursor and perform actions like clicking.

Features:
- Hand detection: The application uses the MediaPipe library to detect the user's hand in real-time from the webcam feed.
- Cursor movement: By tracking the position of the thumb and index finger, the program calculates the movement of the cursor on the screen. Moving the thumb and index finger closer or further apart controls the cursor's speed.
- Clicking action: When the distance between the thumb and index finger is within a defined threshold, a click action is triggered, emulating a mouse click.

Requirements:
- Python 3.x
- OpenCV (cv2)
- Mediapipe
- PyAutoGUI

Usage:
1. Clone the repository or download the source code files.
2. Install the required Python libraries mentioned in the requirements.
3. Connect a webcam to your system.
4. Run the virtual_mouse.py script.
5. A new window will open displaying the webcam feed with the detected hand landmarks and cursor movement.

Customization:
- Cursor Speed: You can adjust the CURSOR_SPEED constant to modify the cursor movement speed.
- Gesture Thresholds: The THUMB_INDEX_DISTANCE_THRESHOLD constant defines the distance threshold between the thumb and index finger for triggering a click action. You can adjust this threshold based on your preference.

Limitations:
- This implementation currently supports single-hand detection and control. Multiple hands may cause unpredictable behavior.
- Lighting conditions and hand orientation may affect the accuracy of hand detection and gesture recognition.

Contributions:
Contributions to the project are welcome. Feel free to create issues or submit pull requests with any improvements or bug fixes.

![image](https://github.com/GuhanAein/VirtualMouse/assets/102289063/e6e53e23-d834-42c7-8284-9097871af24a)


