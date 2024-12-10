# Voice-to-Voice Translation App

This is an interactive **Voice-to-Voice Translation App** built using **Streamlit**, **Google Translate API**, **gTTS (Google Text-to-Speech)**, and **SpeechRecognition**. The app allows users to speak in their native language, translate the spoken text into a target language, and hear the translated text via speech output.

## Features

- **Voice Input:** Record your speech using the microphone.
- **Real-time Translation:** Translates spoken text into a selected target language.
- **Text-to-Speech Output:** Converts the translated text back into speech, enabling users to hear the translation.

## Requirements

To run this app, you will need to install the following Python libraries:

- `streamlit`
- `googletrans`
- `gtts`
- `SpeechRecognition`
- `playsound`

You can install them using `pip`:

```bash
pip install streamlit googletrans gtts SpeechRecognition playsound
Additionally, you need to install PyAudio for microphone input:

bash
Copy code
pip install pyaudio
How to Run
Clone this repository or download the necessary files.

Ensure you have the required libraries installed.

Run the following command to start the Streamlit app:

bash
Copy code
streamlit run app.py
Open the app in your web browser (usually at http://localhost:8501).

Usage
Choose the target language: Select the language you want to translate your speech into from the dropdown list.
Record your speech: Click on the "Record and Translate" button to start recording your voice.
Listen to the translated speech: After the translation is complete, the app will speak the translated text aloud.
Supported Languages
The app supports a variety of languages, thanks to the googletrans API. You can select any of the languages listed in the dropdown menu.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Streamlit: A powerful framework for creating web apps from Python scripts.
Googletrans: Python wrapper for Google Translate API.
gTTS (Google Text-to-Speech): A library and CLI tool to interface with Google Text-to-Speech API for speech synthesis.
SpeechRecognition: A library for recognizing speech and converting it to text.
arduino
Copy code

This `README.md` describes the purpose of the app, how to set it up and run it, its features, and dependencies. You can modify it to suit any changes or additional features you may add later.





