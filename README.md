# Language-Translation
Voice-controlled translator and text-to-speech application supporting multiple languages.

## Overview

This project is a voice-controlled translator and text-to-speech application that translates spoken input into a specified language and plays the translated text aloud. It leverages speech recognition and translation APIs to enable seamless language translation through voice commands.

## Features

- **Voice Input:** Captures spoken commands using a microphone.
- **Language Translation:** Translates spoken input into the desired target language.
- **Text-to-Speech:** Converts translated text to speech and plays it aloud.
- **Multi-Language Support:** Supports a wide range of languages for translation.

## Dependencies

- `speech_recognition`: For capturing and recognizing spoken input.
- `googletrans`: For translating text into different languages.
- `gtts`: For converting text to speech.
- `playsound`: For playing audio files.
- `os`: For file handling operations.

## Usage

1. **Run the Application:**
   Execute the Python script to start the application.

2. **Provide Voice Input:**
   Speak the text you want to translate into the microphone.

3. **Select Target Language:**
   Enter the desired language for translation when prompted.

4. **Receive Translated Speech:**
   The application will convert the translated text to speech and play it aloud.

## Code Explanation

- **Imports and Setup:**
  - `speech_recognition` is used to capture and recognize spoken input.
  - `googletrans` handles the translation of text.
  - `gtts` is used for text-to-speech conversion.
  - `playsound` plays the generated audio file.
  - `os` is used for file operations.

- **Functions:**
  - `takecommand()`: Captures voice input and returns the recognized text.
  - `destination_language()`: Prompts the user to enter the target language for translation.

- **Translation and Speech Synthesis:**
  - The captured voice input is translated into the specified language.
  - The translated text is converted to speech and saved as an audio file.
  - The audio file is played, and then deleted.
