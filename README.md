# AI-Powered Home Security System

An AI-powered access-control project that combines webcam-based face recognition with real-time hand gesture verification using Python, OpenCV, and MediaPipe.

## Overview

The system provides a two-step authentication workflow:

1. Detect and recognize an authorized face.
2. Verify a required hand gesture.
3. Grant or deny access based on the authentication result.

The project also includes utilities for face preprocessing, system launching, and setup testing.

## Key Features

- Webcam-based face detection and recognition
- Face preprocessing and normalization
- Real-time hand gesture recognition
- Dual-step authentication
- Access granted/denied workflow
- Configurable face dataset
- Setup and dependency testing
- Modular Python implementation

## Technologies

- Python
- OpenCV
- MediaPipe
- NumPy

## Project Structure

```text
ai-powered-home-security-system/
├── README.md
├── SETUP_GUIDE.md
├── requirements.txt
├── launch.py
├── secure_entry_system.py
├── gesture_recognition.py
├── preprocess_faces.py
└── test_setup.py
```

## Main Files

- `secure_entry_system.py` — main secure-entry/authentication workflow
- `gesture_recognition.py` — real-time hand gesture recognition
- `preprocess_faces.py` — face preprocessing utility
- `launch.py` — project launcher
- `test_setup.py` — setup/environment testing
- `SETUP_GUIDE.md` — project setup instructions
- `requirements.txt` — Python dependencies

## How It Works

```text
Webcam
   │
   ├── Face Detection / Recognition
   │
   └── Hand Gesture Verification
             │
             ▼
       Authentication
          /       \
       Pass       Fail
        │           │
   Access Flow   Access Denied
```

## Installation

1. Clone the repository.
2. Create and activate a Python virtual environment.
3. Install the dependencies:

```bash
pip install -r requirements.txt
```

4. Follow `SETUP_GUIDE.md` for project-specific configuration.
5. Run the setup test:

```bash
python test_setup.py
```

6. Launch the project using the project's launcher:

```bash
python launch.py
```

## Important Notes

- Configure your own local dataset/path before running the system.
- Do not upload private face images or other personal data to a public repository.
- Do not commit passwords, API keys, credentials, or `.env` files.
- Hardware-specific functionality should only be described as implemented if the corresponding code and hardware configuration are present.

## Future Improvements

Potential extensions include stronger face-recognition models, improved robustness under different lighting conditions, additional authentication methods, and hardware-based locking/alert integration.

## Author

**Chirag Khandelwal**

B.Tech — Computer Science (AIML)  
Manav Rachna University
