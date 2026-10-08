# Emotion Detection (oaqjp-final-project-emb-ai)

**Project Name:** Emotion Detection (oaqjp-final-project-emb-ai)

An AI-based web application developed using Python, Flask, and the IBM Watson NLP Emotion Detection library.

## Project Details
- **Project Name:** Emotion Detection
- **Original Repository:** oaqjp-final-project-emb-ai
- **Framework:** Flask
- **NLP Service:** IBM Watson NLP Emotion Predict

## Features
- Detects five core emotions: Anger, Disgust, Fear, Joy, and Sadness.
- Identifies the dominant emotion from the input statement.
- Modularized as a Python package (`EmotionDetection`).
- Comprehensive unit test suite using `unittest`.
- Deployed with a responsive web interface using Flask.
- Robust error handling for invalid or blank text (HTTP status code 400).
- Static code analysis compliant with PEP 8 scoring 10.00/10 on `pylint`.

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/pratikpawar491212/emotion-detection.git
   ```
2. Install dependencies:
   ```bash
   pip install flask requests pylint
   ```
3. Run the application:
   ```bash
   python server.py
   ```
4. Open your browser and navigate to `http://localhost:5000`.
