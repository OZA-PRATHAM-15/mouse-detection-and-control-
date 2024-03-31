# Virtual Hand-Controlled Mouse

Welcome to the Virtual Hand-Controlled Mouse project! This project enables you to control your computer's mouse cursor using your hand gestures captured by your webcam.

## Overview

This program utilizes the OpenCV and Mediapipe libraries to detect and track hand landmarks in real-time. By moving your index finger and thumb, you can perform mouse clicks and cursor movements respectively.

## Dependencies

Ensure you have the following dependencies installed:

- Python 3.x
- OpenCV (`pip install opencv-python`)
- Mediapipe (`pip install mediapipe`)
- PyAutoGUI (`pip install pyautogui`)

## Usage Instructions

1. **Clone the Repository:**
   Clone this repository to your local machine using the following command:

2. **Navigate to Project Directory:**
Open your terminal or command prompt and change directory to the cloned project folder:

3. **Run the Script:**
Execute the Python script `virtual_mouse.py` using the following command:

4. **Control the Mouse:**
Once the script is running, point your hand towards your webcam. Move your index finger to click and move your thumb to control the cursor. Adjust the sensitivity as needed by modifying the thresholds in the code.

## Important Notes

- Ensure your webcam is connected and functioning properly.
- Make sure your hand is well-illuminated and clearly visible to the webcam for optimal detection.
- The program works best in well-lit environments with minimal background clutter.

## Customization

Feel free to customize the code to suit your preferences. You can adjust parameters such as thresholds for click detection and cursor movement speed based on your needs.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. We welcome any contributions or suggestions for improvement.

Enjoy using the Virtual Hand-Controlled Mouse!
