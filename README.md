# 🌟 Oasis Infobyte (OIBSIP) Python Development Portfolio

Welcome to my master repository for the **Oasis Infobyte (OIBSIP) Python Development Internship**. This repository contains five distinct Python applications, ranging from command-line utilities to advanced, cryptographically secure graphical desktop applications built with Tkinter, SQLite3, and asynchronous sockets.

---

## 👨‍💻 About the Developer
**Muhammad Saleem (Kamran)**
* **Role:** AI Engineer & Data Analyst
* **University:** Sindh Agriculture University (Class of 2028)
* **Focus:** Data-driven web applications, bioinformatics, and scalable business platforms.

---

## 📂 Project Structure & Task Breakdown

### [Task 1: AI Desktop Voice Assistant](./Task1_Voice_Assistant)
A lightweight, responsive voice-controlled desktop assistant bridging the gap between natural human speech and automated computer tasks.
* **Tech Stack:** `Python`, `SpeechRecognition`, `pyttsx3`, `PyAudio`
* **Features:** Offline Text-to-Speech (TTS), real-time microphone audio parsing, automated web searches, live system chronometrics, and robust ambient noise handling.

### [Task 2: Advanced BMI Calculator](./Task2_BMI_Calculator)
A comprehensive Body Mass Index calculator featuring a fully functional graphical user interface and persistent user data tracking.
* **Tech Stack:** `Python`, `tkinter`, `sqlite3`, `matplotlib`
* **Features:** Responsive Tkinter GUI, strict input validation, real-time color-coded health categorization, SQLite database integration for multi-user history, and data trend visualization.

### [Task 3: Secure Password Generator](./Task3_Password_Generator)
A cryptographically secure password generation tool designed to meet strict IT security and entropy standards.
* **Tech Stack:** `Python`, `tkinter`, `secrets`, `pyperclip`
* **Features:** Built with the `secrets` module (bypassing the insecure `random` library), dynamic Tkinter GUI with length sliders, guaranteed character-type injection, ambiguous character filtering, strength indicators, and one-click clipboard copying.

### [Task 4: Real-Time Weather Application](./Task4_Weather_App)
A modern graphical weather dashboard that fetches real-time meteorological data and forecasts via external APIs.
* **Tech Stack:** `Python`, `requests`, `tkinter`, `Pillow`
* **Features:** IP-based automatic location detection, live API integration (OpenWeatherMap), dynamic weather icon rendering downloaded straight to memory, Celsius/Fahrenheit toggling, and 12-hour predictive forecasting panels.

### [Task 5: Multi-Room Chat Application](./Task5_Chat_App)
A robust Client-Server architecture utilizing JSON over asynchronous sockets for real-time networking.
* **Tech Stack:** `Python`, `socket`, `threading`, `tkinter`, `sqlite3`
* **Features:** Multi-room chat environments, user authentication with SQLite database storage, dynamic Emoji shortcode translation, persistent message history loading, and cross-platform desktop notifications for background alerts.

---

## 🚀 Installation & Usage

To test any of the applications locally, clone this master repository and install the global requirements:

```bash
# 1. Clone the repository
git clone [https://github.com/YOUR-USERNAME/OIBSIP-Python-Internship.git](https://github.com/YOUR-USERNAME/OIBSIP-Python-Internship.git)
cd OIBSIP-Python-Internship

# 2. Install all required dependencies
pip install SpeechRecognition pyttsx3 PyAudio matplotlib pyperclip requests Pillow plyer
