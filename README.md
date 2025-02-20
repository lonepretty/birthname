# Live Hand Gesture Tracking and Recognition

## Overview

This project is a Live Hand Gesture Tracking and Recognition system using **Mediapipe** and **OpenCV**. It captures hand gestures via a webcam, processes them using **Mediapipe Hands**, and classifies them into predefined custom gestures. The recognized gestures are then converted into text.

## Features

- **Real-time Hand Detection** using **Mediapipe Hands**
- **Gesture Classification** for predefined custom gestures
- **Text Conversion** for recognized gestures
- **User-friendly and efficient** implementation

## Requirements

Make sure you have the following installed:

- Python 3.x
- OpenCV (`cv2`)
- Mediapipe
- NumPy

Install dependencies using:

```bash
pip install opencv-python mediapipe numpy
```

## How It Works

1. Captures real-time hand gestures using a webcam.
2. Uses **Mediapipe Hands** to detect hand landmarks.
3. Extracts key landmark points and maps them to a trained model.
4. Classifies the gesture based on predefined hand positions.
5. Displays the recognized gesture as text.

## Usage

Run the script using:

```bash
python main.py
```

## Customizing Gestures

You can add custom gestures by collecting new hand landmark data and training a classifier model. Modify `train_model.py` to add new labels and retrain the model.

## Future Improvements

- Expand gesture dataset for better accuracy
- Add voice synthesis for text output
- Enhance model to support ASL gestures

## Contributing

Feel free to fork and contribute to this project. Open an issue for suggestions or bug reports.
