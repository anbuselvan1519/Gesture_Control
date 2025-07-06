GESTURE CONTROL SYSTEM USING MEDIAPIPE & OPENCV
===============================================

A real-time hand gesture recognition project that uses your webcam to detect simple hand gestures and control system-level actions. Built using Python, OpenCV, and MediaPipe.

---------------------------------------
FEATURES
--------

- Real-time gesture recognition using webcam
- Recognizes gestures like:
    - Thumbs Up → Opens WhatsApp Desktop
    - Fist → Opens File Explorer
    - Open Palm → Locks the screen
- Easy to extend for more gesture-based controls

---------------------------------------
PROJECT STRUCTURE
------------------
```
gesture-control/
├── gesture_control.py         # Main script
├── requirements.txt           # Dependencies
├── README.txt                 # Project information
```
---------------------------------------
INSTALLATION
------------

1. Clone this repository:
    git clone https://github.com/anbuselvan1519/gesture-control.git
    cd gesture-control

2. Install dependencies:
    pip install -r requirements.txt

3. Run the application:
    python gesture_control.py

---------------------------------------
REQUIREMENTS
------------

- Python 3.8 or above
- Webcam
- Libraries:
    - opencv-python
    - mediapipe

Install them manually if needed:
    pip install opencv-python mediapipe

---------------------------------------
SUPPORTED GESTURES
-------------------

| Gesture      | Action                  |
|--------------|--------------------------|
| Thumbs Up    | Launch WhatsApp Desktop |
| Fist         | Open File Explorer       |
| Open Palm    | Lock the screen          |

---------------------------------------
FUTURE ENHANCEMENTS
--------------------

- Add custom gestures (e.g., swipe, zoom)
- Audio/visual feedback for gestures
- GUI for gesture-action mapping
- Control music, browser, volume, brightness, etc.

---------------------------------------
LICENSE
-------

This project is licensed under the MIT License.
See the LICENSE file for details.

---------------------------------------
AUTHOR
-------

Created with ❤️ by Anbuselvan S
GitHub: https://github.com/anbuselvan1519
