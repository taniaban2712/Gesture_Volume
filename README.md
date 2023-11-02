# Control the Beats
This project implements a gesture volume control system using OpenCV and Python. The system uses MediaPipe Hands to track the user's hand landmarks and uses the distance between the thumb and index finger to control the volume.


## Prerequisites:
* Python 3.8.10
* OpenCV
* Mediapipe
* Pycaw

## Installations:
```
pip install opencv-python mediapipe pycaw
```
## Getting Started:
* Clone this Respository:
  ```
  git clone https://github.com/taniaban2712/Gesture_Volume
  ```
* Run the following commands on the terminal
  ```
  cd Gesture_Volume
  python volumecontrol.py
  ```
The system will start capturing video from your webcam and tracking your hand. To control the volume, simply move your thumb and index finger closer together to decrease the volume or further apart to increase the volume.
  
