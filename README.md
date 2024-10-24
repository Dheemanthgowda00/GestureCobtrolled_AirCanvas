# GestureControlled_AirCanvas

## Overview
This project is a hand-drawing application that allows users to create drawings using hand gestures. Utilizing MediaPipe for hand tracking and OpenCV for rendering, users can select different drawing tools (line, rectangle, circle, draw, and erase) based on their hand position. The application provides an interactive interface for creative expression using hand movements.

## Features
- **Hand Tracking**: Uses MediaPipe to detect and track hand landmarks in real-time.
- **Drawing Tools**: Select between various drawing tools:
  - **Line**: Draw straight lines by holding a finger.
  - **Rectangle**: Draw rectangles by selecting two opposite corners.
  - **Circle**: Draw circles based on the distance between two points.
  - **Free Drawing**: Draw freely using hand gestures.
  - **Erase**: Erase parts of the drawing.
- **User Interface**: Displays selected tool and a tools palette for easy access.
- **Fullscreen Mode**: The application runs in fullscreen mode for an immersive experience.

## Requirements
- Python 3.x
- OpenCV
- MediaPipe
- NumPy

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/hand-drawing-app.git
   cd hand-drawing-app
