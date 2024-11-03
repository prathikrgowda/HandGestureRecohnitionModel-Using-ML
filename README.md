Hand Gesture Recognition and Voice Conversion

Overview

This project aims to bridge communication gaps for the deaf and aphonic communities by converting hand gestures to voice, text to speech, voice to text, and voice to hand gestures. Utilizing advanced libraries such as OpenCV, MediaPipe, TensorFlow, and several others, this project leverages computer vision and machine learning to interpret hand gestures and convert them into spoken words or text, and vice versa.

Features

Gesture to Voice: Converts recognized hand gestures into spoken words.
Text to Speech: Converts input text into audible speech.
Voice to Text: Translates spoken words into text.
Voice to Gesture: Shows a gesture corresponding to spoken words.

Prerequisites

Before running this application, ensure you have Python installed on your system. You can download it from python.org. Additionally, you will need to install several Python libraries.

Installation
Clone the repository to your local machine or download the project files.

Open your terminal or command prompt and navigate to the project directory.

Install the required Python libraries by running the following command:

bash
pip install opencv-python numpy mediapipe tensorflow pygame gTTS mutagen speech_recognition pyttsx3 Pillow
Ensure you have the necessary model files and data in the project directory. Specifically, for gesture recognition, ensure mp_hand_gesture model and gesture.names files are placed in the correct directory.

Usage
To run the application, navigate to the project directory and execute the interface script:

bash
python interface.py
This command launches a GUI with options to access all functionalities of the project. From the GUI, you can select the desired feature and follow the on-screen instructions to use it.

Note
Ensure your system's microphone and webcam are correctly configured and accessible for voice and gesture recognition features.
Modify file paths in the scripts if necessary to match your directory structure.
Troubleshooting
If you encounter any issues, first check that all prerequisites are correctly installed and configured. For hardware-related issues, verify that your microphone and webcam are properly set up. For any library-specific issues, consult the documentation for those libraries.

Contributing
Contributions to improve the project are welcome. Please feel free to fork the repository and submit pull requests.
