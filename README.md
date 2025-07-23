# 🖱️ Trol Mouse: Hand & Eye Controlled Virtual Mouse

Trol Mouse is a Python-based virtual mouse project that allows users to control their computer cursor using either **hand gestures** or **eye movements**. Built using cutting-edge computer vision and automation libraries, this project reflects my excitement for exploring natural and touchless ways of interacting with technology.

## 🚀 Features

- ✋ Hand gesture control (move, click)
- 👁️ Eye movement and blink-based control
- 🎯 Mode switching capability
- ⚡ Real-time responsiveness
- 🖥️ Works with a standard webcam (no additional hardware required)

## 🛠️ Technologies Used

- **Python** – Core programming language
- **OpenCV** – Image processing and webcam integration
- **MediaPipe** – Hand and face mesh landmark detection
- **PyAutoGUI** – Controlling mouse movements and clicks
- **Pynput** – mouse event handling
- **NumPy** – Numerical calculations and optimizations

## How It Works

Hand Mode: Tracks index and thumb finger using MediaPipe, and simulates mouse movement and clicks via PyAutoGUI.
Eye Mode: Uses face mesh detection to identify eye landmarks, detect blinks, and control cursor based on gaze direction.

## Why I Built This

I've always been fascinated by computer vision and the idea of touchless interaction. This project was my way of experimenting with intuitive, accessible technology. Watching the mouse respond to my gestures and blinks was an incredibly exciting and rewarding experience!

## Future Improvements
Add GUI to toggle between modes

Support for drag and scroll

Adaptive sensitivity calibration

Add voice command integration
    
