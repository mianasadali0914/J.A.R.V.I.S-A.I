# 🤖 J.A.R.V.I.S. AI — Python Voice Assistant

J.A.R.V.I.S. AI is a Python-based voice assistant inspired by the intelligent assistant from Iron Man. The project is designed to accept voice commands, open websites, tell the current time, and support AI-powered conversations.

The goal of this project is to explore artificial intelligence, speech recognition, and desktop automation using Python.

## ✨ Features

- 🎙️ **Voice Recognition:** Accepts voice commands through a microphone.
- 🌐 **Website Launcher:** Opens websites such as YouTube, Google, and Wikipedia.
- 🧠 **AI Conversations:** Uses an AI API to generate responses to user queries.
- 🕒 **Time Information:** Tells the current time.
- 🎵 **Music Playback:** Includes a command for playing a local music file.
- 💬 **Chat History:** Maintains conversation text during the current session.
- 📝 **AI Text Generation:** Generates AI responses and saves them in local files.
- 🔄 **Chat Reset:** Includes an option to reset the current conversation.

## 🛠️ Technologies Used

- **Python** — Main programming language.
- **SpeechRecognition** — Converts spoken commands into text.
- **OpenAI API** — Provides AI-generated responses.
- **NumPy** — Numerical computing library.
- **Webbrowser** — Opens websites from Python.
- **OS Module** — Interacts with operating-system commands and files.
- **Datetime** — Retrieves the current date and time.

## 📂 Project Structure

```text
JARVIS-AI/
│
├── main.py          # Main assistant code (use your actual filename)
├── config.py        # API key configuration
├── README.md        # Project documentation
├── Openai/          # Folder for generated AI text files
└── requirements.txt # Python dependencies
```

*Note: This is an example structure. Adjust the filenames and folders to match your actual repository.*

## ⚙️ Requirements

- Python installed on your computer.
- A working microphone.
- An internet connection for online speech recognition and AI services.
- An API key for the configured AI service.
- The required Python packages.

## 📦 Installation

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your repository's actual URL.

### 2. Open the Project Folder

```bash
cd JARVIS-AI
```

### 3. Install the Required Packages

```bash
python -m pip install openai SpeechRecognition numpy
```

If microphone support is unavailable, you may also need a compatible audio package, such as PyAudio.

### 4. Configure Your API Key

The original code imports an API key from `config.py`.

Create or configure that file according to your code's requirements. **Never upload your real API key to GitHub.** Store secrets in environment variables or a local `.env` file excluded from version control.

### 5. Run the Assistant

```bash
python main.py
```

Replace `main.py` with the actual name of your Python file.

## 🗣️ Example Commands

The assistant's code includes commands intended to:

- Open YouTube.
- Open Google.
- Open Wikipedia.
- Tell the current time.
- Play a configured music file.
- Start an AI-powered conversation.
- Reset the chat.
- Exit the assistant.

The exact commands depend on the conditions defined in the Python script.

## ⚠️ Current Limitations

This project is a work in progress.

- The AI integration uses an older OpenAI API interface that may no longer work.
- Some commands use macOS-specific functionality and may need modification for Windows or Linux.
- The music command references a local file path that must be updated for your computer.
- Speech recognition depends on microphone access and network availability.
- Error handling and compatibility can be improved.

## 🚀 Future Improvements

- Migrate to a supported AI API interface.
- Improve voice recognition and error handling.
- Add natural text-to-speech support.
- Build a graphical user interface.
- Add customizable voice commands.
- Improve Windows and Linux compatibility.
- Add conversation memory.
- Implement safer desktop automation.
- Organize the code into separate modules.

## 🎯 Project Objective

The objective of J.A.R.V.I.S. AI is to develop practical skills in Python programming, artificial intelligence integration, speech recognition, and automation while building a personal voice assistant.

## 👨‍💻 Author

**Asad Ali**

Computer Science & Cybersecurity Enthusiast

## 📜 License

This project is intended for learning and experimentation. Add a suitable open-source license if you want others to reuse or distribute your code.
