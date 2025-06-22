🎙️ GroqTalk AI  
Real-Time Audio Transcription with Whisper + Groq

📖 Overview

**GroqTalk AI** is a desktop application that transforms audio files into accurate text transcriptions using **OpenAI Whisper (via Groq API)**. It provides a simple, elegant GUI built with **Tkinter** and allows users to upload audio, transcribe it in seconds, and save the output as a `.txt` file.

This project bridges the power of **real-time AI inference** with **user-friendly tools** — perfect for podcasters, students, journalists, or developers who want quick, on-device transcription.

🚀 Features

- 🎧 Upload audio files (`.mp3`, `.wav`, `.m4a`, `.ogg`)
- ⚡ Transcribe instantly using Whisper Large v3 via Groq API
- 💬 Clean and readable transcription display
- 💾 Save output as a `.txt` file
- 💻 Cross-platform GUI built using `Tkinter`
- 🔐 Uses `.env` for secure API key storage

🧰 Tech Stack

- Python 3.x  
- Tkinter (GUI)  
- Groq API + Whisper model  
- Requests, dotenv, base64

📁 Project Structure

groqtalk-ai/
├── gui_app.py           # Main GUI application
├── groq_transcribe.py   # Backend CLI-based transcription
├── .env                 # Stores API key
├── audio/               # Folder for test audio files
├── README.md

![Screenshot 2025-06-22 082637](https://github.com/user-attachments/assets/fdcf8a8e-b754-4948-92d5-72fe2beb6d3a)

![Screenshot 2025-06-22 082657](https://github.com/user-attachments/assets/0ae80ad4-d441-4d7d-b2f0-e5e7dae25542)


🎯 Use Cases

🗣️ Podcast and meeting transcription
🎓 Lecture and study note creation
📱 Voice notes to text
📰 Journalism and interviews
🧪 AI + audio project demos

📜 License
This project is open-source and licensed under the MIT License.

⚡ Built with Groq + Whisper | Fast, simple, accurate audio transcription.

