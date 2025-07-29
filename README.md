
🎥 YouTube Transcript to Detailed Notes Converter :
A Streamlit web app that transforms YouTube video transcripts into structured, point‑wise notes using Google’s Gemini AI.

Whether you’re a student, researcher, or just someone looking to save time, this tool helps you get the key insights from any YouTube video—without watching the entire thing.

 Features
- Transcript Extraction – Fetches transcripts from YouTube videos (manual subtitles, auto‑generated English, and even Hindi/Spanish/French captions).
- AI‑Powered Summaries – Uses Gemini Pro (gemini-1.5-pro) to create detailed, well‑organized notes.
- Technical Focus – Filters out filler words and conversational fluff, keeping the core subject matter.
- Video Thumbnails – Displays the YouTube thumbnail when you paste a valid link.
- Simple Web Interface – Built with Streamlit for an easy, clean user experience.

Tech Stack
- Frontend: Streamlit
- Backend: Python
- AI Model: Google Gemini (gemini-1.5-pro)

Key Libraries:
- streamlit – for the web UI
- youtube_transcript_api – for fetching transcripts
- google-generativeai – to interact with Gemini
- python-dotenv – for managing API keys
- os – for environment handling

 How It Works
- Paste a YouTube link in the Streamlit app.
- The app extracts the video ID and shows its thumbnail.
- Transcript retrieval: It tries manual captions → English auto captions → Hindi/Spanish/French captions.
- The transcript is sent to Gemini AI with a smart prompt designed for technical summaries.
- You instantly get structured, bullet‑point notes from the video content.
