# Emotion Detection Web Application

An AI-based web application developed using Python, Flask, and the IBM Watson NLP Emotion Detection library.

## Features
- Detects five core emotions: Anger, Disgust, Fear, Joy, and Sadness.
- Identifies the dominant emotion from the input statement.
- Modularized as a Python package (`EmotionDetection`).
- Comprehensive unit test suite using `unittest`.
- Deployed with a responsive web interface using Flask.
- Robust error handling for invalid or blank text (HTTP status code 400).
- Static code analysis compliant with PEP 8 scoring 10.00/10 on `pylint`.

## Installation & Setup
1. Clone the repository.
2. Install dependencies:
   pip install flask requests pylint
3. Run the application:
   python server.py
4. Open your browser and navigate to `http://localhost:5000`.
