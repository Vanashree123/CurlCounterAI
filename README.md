# CurlCounterAI

CurlCounterAI uses **MediaPipe** and **OpenCV** to detect body landmarks in real-time via webcam. It calculates joint angles and tracks exercise repetitions, providing visual feedback directly on the screen. Ideal for fitness monitoring, exercise analysis, and AI-based posture tracking.

## Features

- Real-time pose detection using MediaPipe.
- Calculates joint angles (e.g., elbow angle for bicep curls).
- Displays angle values on the webcam feed.
- Tracks exercise repetitions automatically.
- Highlights body landmarks and connections for better visualization.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/PoseAngleTracker.git
Install required dependencies:

bash
Copy
Edit
pip install opencv-python mediapipe numpy
Usage
Run the main script:

bash
Copy
Edit
python pose_angle_tracker.py
Position yourself in front of the webcam.

The script will display:

Real-time pose landmarks

Elbow angle

Exercise repetition count

Press q to quit.

How It Works
Captures webcam feed using OpenCV.

Processes frames with MediaPipe Pose to detect key landmarks.

Calculates joint angles (e.g., elbow) using coordinate geometry.

Displays the angle on the frame and counts repetitions based on angle thresholds.

Example

Elbow angle displayed during bicep curl exercise.

Contributing
Feel free to fork the project, add new features, or optimize performance. Pull requests are welcome!

License
This project is licensed under the MIT License. See the LICENSE file for details.

vbnet
Copy
Edit

I can also generate a **ready-to-use GitHub repository structure** with `pose_angle_tracker.py`, a `requirements.txt`, and a screenshot placeholder if you want.  

Do you want me to do that?
