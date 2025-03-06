# PipelineMeshOnePic
Facial Landmark Detection using MediaPipe and OpenCV
# Facial Landmark Detection

## Description
This Python script leverages Google's MediaPipe library to detect and visualize 468 facial landmarks on a given image using OpenCV for image processing and visualization.

## Requirements
- Python 3.x
- OpenCV (`cv2`)
- MediaPipe (`mediapipe`)

## Installation
Use pip to install the required packages:

```bash
pip install opencv-python mediapipe
```

## Usage
1. Place your desired input image named `photo2.jpg` in the same directory as the script.
2. Run the Python script:

```bash
python your_script_name.py
```

## Functionality
- Loads an image and converts it from BGR to RGB.
- Detects and draws 468 facial landmarks on the image.
- Displays the resulting image in an OpenCV window.

## Notes
- Ensure `photo2.jpg` is available in the directory or modify the filename in the code accordingly.
- Press any key to exit the displayed window.

## Future Improvements
- Add error handling for situations when no face is detected.
- Optionally implement landmark connections for better visualization.
- Adapt the script for real-time face tracking using video or webcam streams.
