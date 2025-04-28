# CLI GPT - Voice-Powered AI Chatbot

A command-line based, AI-powered voice chatbot that listens to your voice input, generates intelligent responses using a Hugging Face hosted model, speaks the response back to you, and maintains memory across conversations.

Built with ❤️ by Shaurya.

---

## 🚀 Features

- 🎤 **Voice Input:** Speak to the chatbot via your microphone.
- 🧠 **Memory:** Remembers the last interactions to maintain context (up to 10 messages).
- 🔥 **Personality:** Responds like a "big brother" — raw, real, and helpful.
- 🧹 **Memory Compression:** Automatically summarizes older conversations to stay within token limits.
- 🎙️ **Voice Output:** Speaks responses using realistic text-to-speech.
- 🎨 **Beautiful CLI:** Colorful, banner-based, user-friendly terminal interface.
- 📝 **Logging:** Saves full conversations to `logs.txt` for future reference.

---

## 📋 Requirements

- Python 3.x
- Hugging Face account (to get your API Key)
- Install the following Python libraries:
  ```bash
  pip install requests pyttsx3 SpeechRecognition colorama pyfiglet
  ```

## ⚙️ Installation
1- Clone the repository:

```bash
get code from sourcecode.py and make a python file consisting that code.
```

2- Installthe dependencies:

```bash
pip install -r requirements.txt
```

(Create a requirements.txt with the following lines if not already created:

```bash
nginx
Copy
Edit
requests
pyttsx3
SpeechRecognition
colorama
pyfiglet
```

3- Set your Hugging Face API Key inside the script:

headers = {"Authorization": "Bearer YOUR_HF_API_KEY"}
```bash
you don't need key now because the code already has key.
```
