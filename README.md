# Blink Counter Using Python & MediaPipe Face Mesh

A real-time Blink Counter application built using Python, OpenCV, and MediaPipe Face Mesh.  
The system detects facial landmarks through a webcam feed and counts eye blinks automatically.

---

# Features

- Real-time face detection
- Eye blink detection
- Blink counter system
- Face Mesh landmark tracking
- Live webcam feed
- FPS display
- Lightweight and fast processing
- Real-time eye aspect monitoring

---

# Tech Stack

## Language
- Python

## Libraries Used
- OpenCV
- MediaPipe
- NumPy

## Installation


1. Clone the repository
git clone https://github.com/omar2301433/blink_counter.git

3. Navigate to project folder
cd blink-counter

5. Create Virtual Environment (Optional)
Windows
python -m venv venv
venv\Scripts\activate
Mac/Linux
python3 -m venv venv
source venv/bin/activate

7. Install Required Libraries
pip install opencv-python mediapipe numpy

or

pip install -r requirements.txt

## How to Run
Run the Python file:
python main.py


## The webcam will open automatically and start detecting:
Face landmarks
Eye movement
Blink count

Press:

q

to exit the application.

## How It Works

Webcam captures live video
MediaPipe Face Mesh detects facial landmarks
Eye landmarks are tracked
Eye blinking ratio is calculated
Blink counter increases when eyes close
MediaPipe Face Mesh

## The project uses MediaPipe Face Mesh to detect facial landmarks in real time.

Features:

468 face landmarks
Accurate eye tracking
Fast processing
Real-time detection

