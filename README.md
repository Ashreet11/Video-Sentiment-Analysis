# 🎭 Emotion Detection from Video using Whisper and VADER

This project performs **emotion and sentiment analysis** on a video using the following steps:
1. Transcribes speech from the video using **OpenAI's Whisper**
2. Cleans and preprocesses the text
3. Detects **emotions** using a custom lexicon
4. Performs **sentiment analysis** using VADER
5. Visualizes emotion distribution with a **pie chart**

---

## 📦 Technologies Used

- Python 🐍
- [moviepy](https://zulko.github.io/moviepy/) – for extracting audio from video
- [Whisper](https://github.com/openai/whisper) – for speech-to-text transcription
- [NLTK](https://www.nltk.org/) – for tokenization & stopword removal
- [VADER Sentiment](https://github.com/cjhutto/vaderSentiment) – for sentiment scoring
- matplotlib – for visualization

---
