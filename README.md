# mpfd
+ A simple wrapper of mediapipe face detection, can replace dlib frontal_face_detector inplace without any other change.
+ More about mediapipe, please see [mediapipe](https://google.github.io/mediapipe/)
### Usage:
    create: detect_mpfd=mpfd()
    detect: faces=detect_mpfd(frame) 
    the result is list of dlib.rectangle