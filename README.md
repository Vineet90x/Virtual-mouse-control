

# Virtual Mouse using Hand Gestures

This project is a virtual mouse system that uses hand gestures to control the mouse cursor. It uses a webcam to capture video, detects hand landmarks, and moves the mouse cursor based on the detected hand movements. Additionally, it supports clicking using thumb and index finger pinching gestures.

## Project Description

The Virtual Mouse project leverages computer vision and machine learning techniques to enable mouse control through hand gestures. It uses the webcam to capture video, processes the frames to detect hand landmarks, and moves the mouse cursor accordingly. The index finger tip controls the cursor movement, and the thumb tip in conjunction with the index finger tip enables clicking actions.

## Installation

To install the necessary modules, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/virtual_mouse.git
   ```

2. Navigate to the project directory:
   ```bash
   cd virtual_mouse
   ```

3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. Install the required modules:
   ```bash
   pip install -r requirements.txt
   ```

Alternatively, you can install the modules individually:
```bash
pip install opencv-contrib-python
pip install numpy
pip install mediapipe
pip install pyautogui
pip install matplotlib
```

## Usage

1. Ensure you are in the project directory and the virtual environment is activated.
2. Run the application:
   ```bash
   python main.py
   ```


## Modules Used

- **cv2 (OpenCV)**: Used for real-time computer vision. It captures video from the webcam and processes the frames.
  - Installation: `pip install opencv-contrib-python`
  
- **numpy**: A fundamental package for scientific computing with Python. It is used here for numerical operations.
  - Installation: `pip install numpy`
  
- **mediapipe**: A framework for building multimodal (e.g., video, audio, and sensor) applied ML pipelines. Used for hand landmark detection.
  - Installation: `pip install mediapipe`
  
- **pyautogui**: A module for programmatically controlling the mouse and keyboard. It is used to move the mouse cursor and simulate mouse clicks.
  - Installation: `pip install pyautogui`
  
- **matplotlib**: A plotting library for the Python programming language and its numerical mathematics extension NumPy. Here, it is used to visualize data if needed.
  - Installation: `pip install matplotlib`

## Features

- Real-time hand detection and tracking.
- Mouse cursor control using index finger tip.
- Mouse clicking using thumb and index finger pinching gestures.
- Smooth cursor movement.

## Output

![virtual mouse](https://github.com/Vineet90x/Virtual-mouse-control/assets/78544085/7554fec7-2910-4bea-bb50-b9ae1d971b31)

