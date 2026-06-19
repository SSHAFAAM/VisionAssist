# VisionAssist – AI Assistant for Visually Impaired

VisionAssist is an AI-powered assistive application designed to help visually impaired and rural users interact with their surroundings independently. The app combines real-time object detection, Indian currency recognition, and voice-guided navigation to provide accessibility and support in daily life.

## Features

### Object Detection
- Detects everyday objects in real time using YOLO
- Announces detected objects using voice output
- Helps users understand their surroundings

### Indian Currency Recognition
- Identifies Indian currency notes accurately
- Useful for visually impaired users during transactions
- Supports multiple denominations

### Voice-guided Navigation
- Provides audio-based navigation assistance
- Helps users move safely from one location to another
- Designed for accessibility-first interaction

## Tech Stack

### AI / ML
- YOLOv5 / YOLOv8
- OpenCV
- Python
- NumPy

### Backend
- Flask

### Frontend / Mobile
- Flutter

### APIs / Services
- Text-to-Speech (TTS)
- Speech Recognition
- Google Maps API (for navigation)

## Project Workflow

1. Capture image/video input
2. Process input using YOLO model
3. Detect objects or recognize currency
4. Convert output into speech
5. Provide navigation instructions through voice

## Use Cases
- Identifying objects like bottles, chairs, doors, etc.
- Detecting Indian currency notes
- Navigating roads and unfamiliar places
- Helping rural users identify tools or signs

## Future Improvements
- OCR for reading text from documents
- Face recognition for known contacts
- Emergency SOS feature
- Offline mode for low-network areas
- Multi-language voice support

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/visionassist.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask server:

```bash
python app.py
```

## Model Training
Custom YOLO training was performed on datasets containing:
- Indian currency notes
- Village tools
- Common household objects
- Directional signs

## Impact
This project aims to improve accessibility, independence, and confidence for visually impaired individuals by using AI as an everyday companion.

## Contributors
Shafana |
Alisha  |
Udaynath

