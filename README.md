# Voice-Based Book Searching System

## Overview
This project is a voice-based book searching system that allows users to search for book details using speech recognition. The system listens to the user's speech input, converts it into text, and searches an Excel file for matching book details. If a match is found, the details are displayed and read out loud using text-to-speech (TTS) functionality.

## Features
- **Speech Recognition**: Uses `speech_recognition` library to capture and process voice input.
- **Excel Book Database**: Stores book details in an Excel file (`books.xlsx`).
- **Text-to-Speech (TTS)**: Uses `win32com.client` to read out book details.
- **Search Functionality**: Matches user input with book titles in the database.

## Technologies Used
- Python
- SpeechRecognition (`speech_recognition`)
- Google Text-to-Speech (`gTTS`)
- Excel Handling (`pandas`, `openpyxl`, `xlrd`, `xlutils`)
- Windows Speech API (`win32com.client`)

## Installation
### Prerequisites
Ensure you have Python installed (recommended version: 3.x). Install the required dependencies using:
```sh
pip install speechrecognition pandas numpy openpyxl xlrd xlutils gtts pywin32
```

### Setup
1. Clone the repository:
```sh
git clone https://github.com/yourusername/voice-book-search.git
```
2. Navigate to the project directory:
```sh
cd voice-book-search
```
3. Place your `books.xlsx` file in the project directory.

