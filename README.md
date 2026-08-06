# Face Recognition System

## Overview

Face Recognition System is a Python-based computer vision application that detects and recognizes human faces using a webcam. The system compares captured facial features with stored images of known people and identifies matching faces in real time.

## Features

* Real-time face detection
* Face recognition using stored images
* Webcam support
* Identifies known and unknown faces
* Automatic face labeling
* Image-based face encoding
* Simple command-line setup

## Technologies Used

* Python 3
* OpenCV
* Face Recognition Library
* Computer Vision

## Project Structure

```text
face-recognition-system/
│
├── face_recognition.py
├── known_faces/
│   ├── Person1.jpg
│   ├── Person2.jpg
│
├── requirements.txt
└── README.md
```

## Requirements

Install the required Python libraries:

```bash
pip install opencv-python face-recognition
```

Or add them to:

```text
requirements.txt

opencv-python
face-recognition
```

## Getting Started

### Prerequisites

* Python 3.x installed
* Webcam connected
* Images of known people stored in the `known_faces` folder

Check Python version:

```bash
python --version
```

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/face-recognition-system.git
```

2. Navigate to the project directory:

```bash
cd face-recognition-system
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Add known face images:

```text
known_faces/
│── John.jpg
│── Alice.jpg
```

5. Run the application:

```bash
python face_recognition.py
```

## Usage

Example:

```text
Face Recognition System Started...

Camera opens automatically.

Detected Face:
Name: John

Detected Face:
Name: Unknown

Press 'q' to exit.
```

## Learning Objectives

This project demonstrates:

* Python programming
* Computer vision concepts
* Face detection and recognition
* Image processing
* OpenCV usage
* Real-time video analysis
* File handling

## Future Improvements

* Add a graphical user interface (GUI)
* Store face data in a database
* Add attendance tracking
* Improve recognition accuracy
* Add security authentication
* Deploy as a web application

## License

This project is open source and available under the MIT License.
