## Overview
Gesture Volume Control is a Python-based project that allows users to control the volume of their computer using hand gestures captured through a webcam. By detecting hand movements and gestures, the system adjusts the system volume accordingly, providing a convenient and intuitive way to manage audio output without the need for physical controls.

## Features
Real-time hand gesture recognition: The system detects hand movements and gestures in real-time using computer vision techniques.
Volume control: Users can control the volume of their computer by performing specific gestures, such as raising or lowering their hand.
Adjustable sensitivity: The sensitivity of gesture recognition can be adjusted to suit the user's preferences and environmental conditions.
User-friendly interface: The system provides visual feedback to the user, indicating the recognized gestures and the corresponding volume adjustments.

## Screenshots


![Screenshot 2024-02-27 143720](https://github.com/harshavangari/gesture-volume-control/assets/115146449/7f9a83f5-ce12-42fa-9c6e-fe78dff02312)

![Screenshot 2024-02-27 143842](https://github.com/harshavangari/gesture-volume-control/assets/115146449/5138acfc-2b41-47e3-9ac6-8a2b6562964e)


## Technologies Used

The following technologies and libraries were used for this project:

- PyCaw: Enables changes in volume.
- HandTracking module: Tracks the fingers and calculates the distance between them.
- mediapipe library: Used for hand tracking.
- cv2

## Installation
Clone the repository:

bash
Copy code
git clone https://github.com/username/gesture-volume-control.git
Install dependencies:

Copy code
pip install opencv-python numpy
## Usage
Run the main script:

css
Copy code
python main.py
Position yourself in front of the webcam and perform gestures to control the volume:

Raise your hand to increase the volume.
Lower your hand to decrease the volume.
Adjust the sensitivity as needed by modifying the corresponding parameter in the script.

## Acknowledgements
This project is inspired by the concept of gesture-based interaction and audio control in modern computing environments.
Special thanks to the developers and contributors of OpenCV and NumPy for their valuable libraries and resources.
## License
This project is licensed under the MIT License - see the LICENSE file for details.
Feel free to explore the repository and contribute to the project.
