# Hand Gesture Volume Control 🎚️✋

A simple Python project that controls system volume using hand gestures, perfect for learning computer vision basics.

## Features ✨
- 📶 Real-time hand tracking
- 🔊 Volume control via thumb-index finger distance
- 📊 Visual volume bar feedback
- 🔇 Mute gesture (pinch)
- 🖥️ Works with Windows volume controls

## Technologies Used 🛠️
- **OpenCV** - Video capture and image processing
- **MediaPipe** - Hand landmark detection
- **Pycaw** - Windows audio control
- **NumPy** - Mathematical calculations

## Installation ⚙️
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hand-gesture-volume-control.git

## Usage 🚀
1. Run the application:

```bash
python VolumeHandControl.py
```
2. Gesture controls:


- 🤏 Pinch thumb and index finger together to mute

- ↔️ Move fingers apart to increase volume

- ↔️ Bring fingers closer to decrease volume

## Project Structure 📂
.
├── HandTrackingModule.py  # Custom hand detection module
├── VolumeHandControl.py   # Main application
├── requirements.txt       # Dependency list
└── README.md             # This file

## Learning Outcomes 📚
This project helped me understand:

- Real-time image processing pipelines

- Hand landmark detection techniques

- System-level integrations in Python

- Mathematical transformations for gesture interpretation

Note: The warnings about TensorFlow Lite are normal and don't affect functionality.
