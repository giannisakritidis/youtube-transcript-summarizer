#  YouTube Transcript Summarizer LLM App

A lightweight Streamlit app that extracts transcripts from YouTube videos and generates high-quality summaries using Google Gemini Pro (via `google-generativeai`).

---

##  Features

-  Input any YouTube video link
-  Automatically extract full transcript
-  Get concise bullet-point summaries using Gemini 1.5 Pro
-  Video thumbnail preview
-  Simple and clean Streamlit interface

---

##  How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/giannisakritidis/youtube-transcript-summarizer.git
cd youtube-transcript-summarizer
```

### 2. Install Dependencies

Make sure you have Python 3.10 or newer:

```bash
pip install -r requirements.txt
```

### 3. Set Your API Key

Create a `.env` file in the root folder:

```bash
touch .env
```

Then add your Google API key inside:

```env
GOOGLE_API_KEY="your_google_api_key_here"
```

> You can get a key from: https://makersuite.google.com/app/apikey

### 4. Launch the App

```bash
streamlit run app.py
```

---

##  Dependencies

- [`streamlit`](https://streamlit.io/)
- [`google-generativeai`](https://github.com/google/generative-ai-python)
- [`youtube_transcript_api`](https://github.com/jdepoix/youtube-transcript-api)
- [`python-dotenv`](https://pypi.org/project/python-dotenv/)

---

##  App Preview

![App Preview](https://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg)

---

##  Important Notes

- The app uses gemini-2.5-pro which may require billing depending on your usage plan.

---

##  License

MIT License – free to use, modify, and share!

---

## 🙌 Contributions

PRs welcome! Feel free to improve the UI, add multilingual support, or swap in open-source LLMs.
