# Gesture based task automation

This project uses the MediaPipe and OpenCV libraries in Python to recognize hand gestures in real-time from a webcam feed. The gestures recognized include thumbs up, palm, thumbs down, peace, and fist.

## Requirements

- Python 3.6+
- MediaPipe
- OpenCV
- NumPy
- Matplotlib
- Tensorflow
- Keras
- OS
- Sklearn


## Installation

1. Clone this repository: `git clone https://github.com/bintibhatt/gesture-based-task-automation.git`
2. Install the required packages: `pip install requirements`.
3. Run the `gesture_recognition.ipynb`.

## Usage

Once the script is running, hold your hand up to the webcam and make one of the gestures listed above. The script will recognize the gesture and take a corresponding action:

- Thumbs up: take a photo and save it to the "images-clicked" directory
- Palm: display the last photo taken in a window
- Thumbs down: delete the last photo taken
- Peace: increase the brightness of the last photo taken by 50 units
- Fist: convert the last photo taken to grayscale

## Usage

The project can be used in various applications, including:

#### Gesture-based human-computer interaction: 
- This project can be useful for educational institutions such as schools, colleges, and universities that often use projectors to teach their students. By integrating this project with a projector, teachers can easily capture and save the notes they write on a whiteboard or blackboard during their lectures. This will not only make it easier for students to keep track of the notes but also help in reducing paper waste. Additionally, this project can be useful in corporate boardrooms, where presentations are made and important ideas and discussions are exchanged.
- Overall, the project has many potential uses in various industries and fields, and its applications are only limited by the creativity and imagination of its users.
