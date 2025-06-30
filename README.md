Voice-Based Sentiment Chatbot
This project implements a speech-driven sentiment analysis chatbot in Python. It uses voice input to interact with the user, performs sentiment analysis on the spoken text, and responds in natural speech with context-aware empathy.

Features
Speech-to-text conversion using Google Speech Recognition

Sentiment analysis with NLTK's VADER sentiment analyzer

Voice-based conversational replies with pyttsx3

Categorizes emotions into five states:

Happy or excited

Calm or content

Neutral

Sad or disappointed

Angry or frustrated

Dynamic spoken responses tailored to the detected emotional state

Easily extensible for advanced conversation logic

Technologies Used
Python 3

speech_recognition

nltk (VADER sentiment analysis)

pyttsx3

pyaudio

Installation and Setup
Install the required Python dependencies:

nginx
Copy
Edit
pip install SpeechRecognition pyttsx3 nltk pyaudio
Download the NLTK VADER lexicon (required for sentiment analysis):

python
Copy
Edit
import nltk
nltk.download('vader_lexicon')
Ensure your microphone is connected and permitted by your operating system.

Save the chatbot code as, for example, chatbot.py.

Run the chatbot:

nginx
Copy
Edit
python chatbot.py
Speak naturally to the chatbot. You can say "exit", "quit", or "stop" to end the conversation.

Project Structure
Copy
Edit
chatbot.py
README.md
Future Enhancements
Integration with advanced large language models such as GPT

Long-term storage of user sentiment history for mental health tracking

Delivery of context-sensitive resources such as guided meditations

Addition of a graphical user interface (GUI) for enhanced usability
