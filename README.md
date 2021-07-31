# volume_controller

## Now controlling your sysytem volume is on your tips. Just move your finger tips in fron of camera and control your system audio.

### Requirements:
-- CV2

-- numpy

-- mediapipe

-- ctypes

-- comtypes

-- pycaw

### Steps :
- Create a model using mediapipe to detect body parts.
- Create a model using mediapipe to make drawing to show detected bodyparts and pose
- using both model detect and create drawings.
- Then access index finger tip and thumb tip points using their indexes values.
  - finget tips index number = 8
  - thumb tips index number = 4
- Calculate the distance between those points and draw a line between them using cv2
- Based on the distance between those points change the system volume.
  - As distance will increase volume will also increase
  - As distance will decrease volume will also decrease

##
### output : volumeController2.mp4, volumeController1.mp4
