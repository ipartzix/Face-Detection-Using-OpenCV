# Face-Detection-Using-OpenCV
This project is a real-time face detection system using OpenCV and Haar cascade classifiers. It captures video from a webcam, detects faces, draws rectangles around them, and displays the count.


This project implements real-time face detection using OpenCV and the Haar cascade classifier.

## Features
- Detects human faces in real-time from a webcam feed.
- Draws rectangles around detected faces.
- Displays the count of detected faces on the screen.
- Press 'A' to exit the program.

## Prerequisites
Ensure you have Python and OpenCV installed before running the script.

### Install Dependencies
```bash
pip install opencv-python
```

## Usage
Run the following command to start face detection:
```bash
python face_detection.py
```

## Code Explanation
1. **Load the Haar Cascade Classifier:**
   - Uses `haarcascade_frontalface_default.xml` to detect faces.
2. **Capture Video from Webcam:**
   - Uses `cv2.VideoCapture(0)` to access the webcam.
3. **Convert Frames to Grayscale:**
   - Improves accuracy and reduces computation time.
4. **Detect Faces:**
   - Uses `detectMultiScale()` for face detection.
5. **Draw Rectangles and Display Count:**
   - Draws green rectangles around detected faces and displays the count.
6. **Exit on Key Press:**
   - Press 'A' to exit the program.

## Demo Screenshots
![Screenshot (262)](https://github.com/user-attachments/assets/1b078a4b-4b7d-42a8-abed-58428c352bf5)
![Screenshot (264)](https://github.com/user-attachments/assets/20fb161d-0150-4f3c-99ea-1b6ed70f2dfd)

## License
This project is open-source and available under the MIT License.

