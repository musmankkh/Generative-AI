# YouTube Video Summarization

## 📌 Overview
In today’s fast-paced world, keeping up with lengthy news reports, interviews, and podcasts is a challenge. Our AI-powered **YouTube Video Summarizer** transcribes, summarizes, and extracts key highlights from videos, complete with speaker detection and multi-language support. This tool helps users quickly grasp video content in minutes.

## 🚀 Features
- **Download YouTube Videos** – Supports video extraction from YouTube.
- **Audio Processing** – Converts video to audio using **MoviePy**.
- **Speech-to-Text** – Uses **OpenAI Whisper** for transcription.
- **Text Summarization** – Generates concise summaries with **BART**.
- **Keyword Extraction** – Identifies key phrases using **KeyBERT**.
- **Sentiment Analysis** – Determines the sentiment of the content.
- **Topic Modeling** – Identifies major discussion points using **LDA**.
- **Named Entity Recognition (NER)** – Extracts important entities.
- **Text Translation** – Translates summaries into different languages.
- **Keyword Visualization** – Displays extracted keywords graphically.

## 🛠️ Installation
```sh
# Install dependencies
pip install yt-dlp openai-whisper transformers torch keybert moviepy sumy scikit-learn matplotlib
```

## 📂 Project Structure
```
📁 Video_Summarization
 ├── 📄 summarize.py       # Main script for summarization
 ├── 📂 data/              # Processed video transcripts
 ├── 📄 requirements.txt   # Dependencies
 ├── 📄 README.md          # Project Documentation
```

## 📌 Usage
```python
from summarize import main

video_path = "C:\\Users\\HP\\Desktop\\GenAI\\Video\\downloaded_video.mp4"
main(video_path)
```

## 🏗️ Technologies Used
- **Python**
- **yt-dlp** (for video downloading)
- **MoviePy** (for extracting audio)
- **Whisper** (for speech-to-text conversion)
- **Hugging Face Transformers** (for summarization and NER)
- **KeyBERT** (for keyword extraction)
- **Latent Dirichlet Allocation (LDA)** (for topic modeling)
- **Matplotlib** (for data visualization)

## 🔥 Future Enhancements
- **Real-time Summarization** – Implement live video summarization.
- **YouTube API Integration** – Automate video fetching and processing.
- **Web Interface** – Develop a user-friendly GUI.

## 🤝 Contributing
Contributions are welcome! Feel free to submit issues and pull requests. 🚀

## 📜 License
This project is licensed under the **MIT License**.
