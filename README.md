# 🧠 Jarvis - Python Voice Assistant

A simple Python-based **voice assistant** that performs tasks based on voice commands. Inspired by Marvel’s Jarvis, this assistant can tell time, search Wikipedia, open websites, and even crack jokes.

---

## 🎯 Features

- 🎤 Voice-controlled assistant using microphone input
- 🕒 Tells current time and date
- 🌐 Opens websites like YouTube and Google
- 📚 Searches Wikipedia and reads summaries
- 😂 Tells random programming jokes
- 👋 Time-based greetings (morning, afternoon, evening)
- ❌ Can be exited with voice commands like "exit" or "bye"

---

## 🛠️ Tech Stack

- **Python 3.10+**
- `pyttsx3` – Text-to-speech engine
- `SpeechRecognition` – Speech-to-text conversion
- `wikipedia` – To fetch summaries
- `pyjokes` – To generate jokes
- `webbrowser` – To open web pages

---

## 🚀 Getting Started

### 📦 Install Dependencies

```bash
pip install pyttsx3 SpeechRecognition wikipedia pyjokes pyaudio

#Run with assistant

python jarvis_assistant.py
