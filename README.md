# volume-control

To implement gesture-based volume control the project utilizes a combination of hardware and 
software components. A webcam captures real-time video input which processed through OpenCV 
and Mediapipe to detect and track hand movements and we use hand landmark model . By PyCaw 
adjusts system volume based on the recognized gestures. Numpy used for  map the range of 
distances between index finger and thumb to the  volume range. Math libraries used for to 
calculate the distance between the index finger to thumb. 
