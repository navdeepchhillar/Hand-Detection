## Hello!!

# Real-Time Hand Detection Using MediaPipe and OpenCV.

### This project performs real-time hand and finger detection using a webcam. It uses MediaPipe for hand tracking and OpenCV for video capture and processing. The detected hand landmarks are annotated on live video frames, and the output is saved as a video file.

## Features :-
    
    - Real-time detection of up to 2 hands
    - Classification of hand as "Left" or "Right"
    - Drawing of 21 hand landmarks and connections
    - Output video saved with all annotations

## First you have to install important dependencies :-

    - pip install opencv-contrib-python
    - pip install numpy
    - pip install mediapipe
    
## Folder Content :-

    .
    ├── Hand-detection.ipynb      # Main script to detect hand and label all 21 landmarks with lines and label hand as left or right 
    ├── output.mp4                # Output video with annotations
    └── README.md

## Itinerary :-

    1. Update directory in codes and install all necessary dependencies.
    2. Run Hand-detection.ipynb and then it will access your default camera using OpenCV.
    3. Then MediaPipe's hand tracking model detects hands in each frame and do check whether it is detecting or not.
    4. After a little output video would be stored to the registered directory.

### That's it!!
