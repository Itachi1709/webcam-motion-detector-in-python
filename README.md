# webcam-motion-detector-in-python
 Webcam motion detection in Python typically involves capturing frames from the webcam, comparing consecutive frames, and identifying changes as motion

Requirement: 
*)Python3
*)OpenCV(libraries)
*)Pandas(libraries)

Install Requirements : Install Python3, install Pandas and OpenCV libraries.

This code captures frames from the webcam, computes the absolute difference between consecutive frames, applies thresholding, and identifies contours of motion. Rectangles are then drawn around areas with significant motion. The process continues until the user presses the 'q' key.
