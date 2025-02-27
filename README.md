# 🎙️ VoiceBot with Siri-like UI

A Python-based voice assistant that listens, transcribes speech, generates responses using GPT-3, and speaks back with a Siri-like animated UI. This project demonstrates the integration of OpenAI's Whisper for transcription, GPT-3 for response generation, and pyttsx3 for text-to-speech.

🚀 Features

🎤 Speech Recognition: Uses OpenAI's Whisper for accurate transcription.

🤖 AI-Powered Responses: Generates conversational replies using GPT-3.

🔊 Text-to-Speech (TTS): Uses pyttsx3 to convert responses into speech.

🎨 Siri-like UI: Animated visual feedback for voice activity.

🛠️ Automatic Silence Detection: Stops recording when silence is detected.

🖥️ System Requirements

Python 3.8+

Works on Windows, macOS, and Linux

Requires an active OpenAI API key

🛠️ Installation

1️⃣ Clone the Repository

git clone https://github.com/ArnavVerma/voicebot.git
cd voicebot

2️⃣ Set Up a Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Set Up API Key

Rename .env.example to .env

Add your OpenAI API Key inside .env

OPENAI_API_KEY=your-api-key-here

🏃‍♂️ Running the Bot

python main.py

Select your microphone device when prompted and start speaking!

📝 Configuration

Modify silence_threshold and silence_duration in record_audio_dynamic() to fine-tune silence detection.

Change engine="text-davinci-003" in generate_response() to a different GPT model if needed.

📜 License

MIT License. Feel free to use and improve!

📅 Project Timeline

Project Started: June 2024

Last Updated: February 27, 2025

🔗 **Made with ❤️ by **Arnav Verma
