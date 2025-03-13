# Moving Object Detection with Alert

This is a simple motion detection system using OpenCV and Pygame. The system detects moving objects through a webcam feed and triggers an alert sound when motion is detected.

## Features
- Real-time motion detection using OpenCV.
- Visual indication with bounding boxes for detected objects.
- Audio alert using Pygame when motion is detected.

## Requirements
Ensure you have the following libraries installed:

```bash
pip install opencv-python imutils pygame
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/arivanan0218/Moving-Object-Detection.git
   cd Moving-Object-Detection
   ```

2. Place an alert sound file named `alert.mp3` in the project directory.

3. Run the Python script:
   ```bash
   python motion_detection.py
   ```

4. Press **'Q'** to stop the motion detection and close the webcam feed.

## Code Explanation
- **OpenCV** handles the webcam feed, image processing, and motion detection.
- **Pygame** is used for playing the alert sound when motion is detected.
- The system compares the first frame with subsequent frames to detect movement and draw bounding boxes around detected objects.

## Customization
- To adjust the sensitivity of motion detection, modify the `area` variable in the code:
  ```python
  area = 500  
  ```

- Replace `alert.mp3` with any custom sound file to personalize the alarm tone.

## Demo
1. The webcam starts capturing the feed.
2. When motion is detected, a green bounding box appears around the moving object, and the alert sound is played.
3. The alarm stops once no motion is detected.

## Contribution
Contributions are welcome! Feel free to submit issues or pull requests to enhance the project.

---
**Author:** Arivanan V.

