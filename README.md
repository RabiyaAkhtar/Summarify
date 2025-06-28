# 📝 Summarify-Chatbot  
**AI-powered YouTube Video Summarizer** | [![Streamlit Demo](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-streamlit-app-link.streamlit.app/)  

Extract key insights from YouTube videos in seconds using NLP. Built with `transformers`, `streamlit`, and `youtube-transcript-api`.  

---

## 🚀 Features  
- **Instant Summaries**: Convert long videos into concise text summaries.  
- **YouTube URL Support**: Just paste the link—no manual transcription needed.  
- **State-of-the-Art NLP**: Powered by Hugging Face’s `facebook/bart-large-cnn` model.  
- **User-Friendly UI**: Clean Streamlit interface with real-time processing.  

---

## ⚙️ Setup  
1. **Clone the repo**:  
   ```bash
   git clone https://github.com/abdullah90907/Summarify-Chatbot.git
   cd Summarify-Chatbot

---

## Dependencies
pip install -r requirements.txt

---

## Run locally
streamlit run app.py

---

🎯 Usage
Enter a YouTube URL in the input box.

Click "Summarize" to generate a condensed transcript.

Adjust summary length via the slider (optional).

---

📦 Dependencies
Python 3.8+

streamlit (UI)

transformers (NLP pipeline)

youtube-transcript-api (transcript extraction)

---

🌟 Future Improvements
Add support for PDF/URL summarization.

Cache transcripts for faster reloads.

Deploy as a public API.

---

