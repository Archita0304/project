# 🎙️ Voice-Based Sentiment Chatbot

This project is a speech-driven sentiment analysis chatbot built in Python. It captures voice input from the user, analyzes its sentiment with NLTK’s VADER, and responds in spoken voice with empathy-aware replies.

---

## ✨ Features

- 🗣️ Speech-to-text conversion via Google Speech Recognition  
- 🧠 Sentiment analysis with NLTK VADER  
- 🔊 Text-to-speech responses with pyttsx3  
- 🎭 Emotion categorization:
  - Happy or excited
  - Calm or content
  - Neutral
  - Sad or disappointed
  - Angry or frustrated  
- 💬 Dynamic conversation based on detected emotion  
- 🧩 Easy to extend and customize

---

## 🛠️ Technologies

- Python 3
- SpeechRecognition
- NLTK
- pyttsx3
- PyAudio

---

## ⚙️ Installation

1. Install the required packages:

   ```bash
   pip install SpeechRecognition pyttsx3 nltk pyaudio
   

2. Download the VADER lexicon (for sentiment analysis):

   ```python
   import nltk
   nltk.download('vader_lexicon');

3. Ensure your microphone is connected and accessible.
   
---

## 🚀 Usage
1. Save the chatbot code as chatbot.py.

2. In your terminal, run:

    ```bash
    python chatbot.py
    Speak naturally to the chatbot.

3. Say “exit”, “quit”, or “stop” to end the conversation.

---

## 🌟 Future Enhancements
Integrate with advanced language models (like GPT)

Add long-term sentiment storage

Provide mental health resources

Implement a graphical user interface (GUI)
