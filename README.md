# 🛒 Walmart Aisle Navigation Voice Assistant

A voice-enabled assistant that helps users navigate inside Walmart stores from one aisle to another using voice commands and intelligent pathfinding. Designed to support individuals with visual impairments or disabilities by delivering spoken instructions.

---

## 📌 Features

- 🎤 **Voice Commands** — Speak your destination (e.g., "Take me to Aisle C2")
- 🗺️ **Shortest Path Navigation** — Calculates optimal path inside a store map
- 🧠 **NLP-Powered Aisle Detection** — Uses spaCy to identify aisle names from voice
- 🔊 **Speech Instructions** — Converts directions to natural spoken instructions using TTS
- ♿ **Accessibility Focused** — Simplified interface with voice-first interaction

---

## 🛠️ Tech Stack

- **Backend**: Python, FastAPI (or Flask)
- **Speech Input**: `speech_recognition`, `pyaudio`
- **Text-to-Speech**: `gTTS`, `pydub`
- **NLP**: `spaCy`, EntityRuler for aisle recognition
- **Pathfinding**: BFS or Dijkstra
- **Visualization** *(optional)*: `matplotlib`

- ---
