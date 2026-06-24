# Emotion Detection AI Web Application

## Project Description
This project is an AI-based web application that performs emotion detection on user-provided text using IBM Watson NLP API. The application is built using Python and Flask.

It analyzes input text and detects the following emotions:
- Anger
- Disgust
- Fear
- Joy
- Sadness

It also returns the dominant emotion in the text.

---

## Technologies Used
- Python
- Flask
- IBM Watson NLP API
- Requests

---

## Features
- Emotion detection from text input
- Flask-based web API
- Handles invalid or empty input
- Unit testing support
- Static code analysis (Pylint)

---

## How to Run the Application

### 1. Install dependencies
pip install flask requests

### 2. Run the Flask app
python3 server.py


### 3. Open in browser
http://127.0.0.1:5000


---

## API Usage


### Endpoint
/emotionDetector?textToAnalyze=I am happy


### Example
http://127.0.0.1:5000/emotionDetector?textToAnalyze=I%20am%20happy
