# 🤖 Quorra – AI Voice Assistant (Python)

Quorra is a **powerful cross-platform AI Voice Assistant** built using **Python**.  
It can **listen, think, and act** using voice commands — from opening apps and websites to chatting with AI, controlling the system, and boosting productivity.

Designed to work on **Windows, macOS, and Linux**.

---

## 🚀 Features

### 🎤 Voice & AI
- Speech Recognition (Google Speech API)
- Text-to-Speech (macOS / Windows / Linux)
- AI Chat using OpenAI
- Context-aware conversation memory

### 🖥️ System Control
- System information (CPU, RAM, OS)
- Battery status
- Lock screen & sleep mode
- Clean temporary files
- Take screenshots

### 🌐 Web & Network
- Open 200+ popular websites
- Google search using voice
- Weather information
- Internet speed test
- Public & local IP address

### 📁 File Management
- Create files (Python, HTML, Text)
- List files from Desktop, Documents, Downloads

### 🎵 Media & Entertainment
- Play local music
- Play YouTube videos
- Tell jokes
- Open Spotify, Netflix, VLC, etc.

### ⏰ Productivity
- Set timers & alarms
- Calculator (basic + advanced math)
- Get date & time
- Screenshot capture

### 📦 Application Launcher
- Open 150+ applications:
  - VS Code, Chrome, Terminal
  - Zoom, Slack, Discord
  - Microsoft Office
  - Adobe & JetBrains tools
  - Media & Dev utilities

---

## 🛠️ Tech Stack

- **Language:** Python 3.9+
- **AI:** OpenAI API
- **Speech:** SpeechRecognition, pyttsx3
- **Automation:** pyautogui, subprocess
- **System:** psutil, platform
- **Web:** requests, webbrowser
- **Media:** pywhatkit, pyjokes
- **Network:** speedtest-cli

---

## 📦 All Python Packages Used

```bash
pip install speechrecognition
pip install openai
pip install pyttsx3
pip install pyautogui
pip install pyperclip
pip install wikipedia
pip install pyjokes
pip install speedtest-cli
pip install pywhatkit
pip install psutil
pip install requests
pip install pillow

```

---
OS-specific Dependencies
# macOS
brew install portaudio

# Linux
sudo apt install espeak portaudio19-dev
---
🔑 API Keys Setup

Edit the Config class in voice_assistant.py:

OPENAI_API_KEY = "your-openai-api-key"
WEATHER_API_KEY = "your-openweathermap-api-key"
NEWS_API_KEY = "your-news-api-key"


⚠️ Never push real API keys to GitHub

---
2️⃣ Run the Assistant
python voice_assistant.py


Missing packages are auto-installed on first run.

🗣️ Example Voice Commands
"Open YouTube"
"What is the weather in Delhi"
"Play music"
"Set a timer for 10 seconds"
"Take a screenshot"
"Tell me a joke"
"Calculate square root of 144"
"Open VS Code"
"Check internet speed"

🧠 Smart Capabilities

Auto OS detection (Windows / macOS / Linux)

Handles speech errors gracefully

Modular & scalable code structure

Secure file operations

Multi-tasking & automation ready

📌 Project Structure
├── voice_assistant.py
├── README.md
├── AI_Responses/
│   └── saved_ai_outputs.txt
---

🚧 Future Enhancements

GUI using Tkinter / PyQt

Wake-word detection

Face recognition

WhatsApp & Email automation

Plugin architecture

Mobile app integration
---
👨‍💻 Author

Sandeep
Full Stack Developer | AI & ML Enthusiast
🎓 B.Tech Computer Science (2025)
📍 India

---

⭐ Support

If you like this project:

⭐ Star the repository

🍴 Fork it

🧠 Improve & contribute

📜 License

This project is licensed under the MIT License.


---

### 🔥 Next (optional – tell me)
Main ye bhi bana deta hoon:
- `requirements.txt`
- `.env` + `.gitignore`
- GitHub repo **description + tags**
- **Resume-ready project explanation**
- **Interview explanation (Hindi + English)**

Bas bolo 🚀
