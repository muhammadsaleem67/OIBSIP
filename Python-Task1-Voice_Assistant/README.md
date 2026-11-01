# 🎙️ Python Desktop Voice Assistant

A lightweight, responsive voice-controlled desktop assistant built in Python. This project bridges the gap between natural human speech and automated computer tasks, featuring offline text-to-speech feedback, robust error handling, and dynamic web integration.

## ✨ Key Features

* **Natural Voice Recognition:** Captures and processes microphone audio in real-time using Google's Speech API.
* **Offline Text-to-Speech (TTS):** Provides instant, localized vocal feedback using `pyttsx3` with an optimized speaking rate.
* **Automated Web Search:** Listens for a specific query and automatically launches your default browser with Google search results.
* **Live Chronometrics:** Accurately calculates and reports the current system time and date on command.
* **Graceful Error Handling:** Intelligently catches and responds to ambient noise, unrecognizable audio, and network dropouts without crashing the application.

## 🛠️ Tech Stack & Dependencies

* **Language:** Python 3.x
* **SpeechRecognition:** Audio parsing and API translation.
* **pyttsx3:** Offline, system-native voice synthesis.
* **PyAudio:** Hardware microphone streaming.
* **Built-in Modules:** `datetime` (time formatting), `webbrowser` (OS browser integration).

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/python-voice-assistant.git](https://github.com/YOUR-USERNAME/python-voice-assistant.git)
   cd python-voice-assistant
