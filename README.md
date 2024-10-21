# 🎤 Groq Whisper Transcription App
A Streamlit-based web application that transcribes audio files using OpenAI's Whisper API. You can either upload an MP3 file or input a YouTube URL to convert video audio into text within seconds.

## Features
- **Upload MP3 Audio:** Upload an MP3 file, re-encode it to an efficient OGG (Opus) format, and get a transcription.
- **YouTube Audio Transcription:** Enter a YouTube video URL, download the audio, convert it to OGG, and transcribe it.
- **Streamlined Audio Processing:** The app optimizes file size by converting audio to Opus format and embedding it for playback.
- **Whisper API: Leverages OpenAI's fast and accurate whisper-large-v3 model for speech-to-text transcription.

## Installation
1. **Clone the repository:**

```bash
git clone https://github.com/your-username/Groq-Whisper-Transcription-App.git
cd Groq-Whisper-Transcription-App
```

2. **Set up a virtual environment** (optional):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

4. **Set up your environment variables:** Create a `.env` file in the root directory and add your Groq API key:

```bash
GROQ_API_KEY=your_groq_api_key
```

5. Run the app:

```bash
streamlit run app.py
```

## How to Use
### MP3 Upload
1. In the "📂 Upload Audio" tab, upload an MP3 file.
2. The file will be processed, re-encoded, and ready for transcription.
3. Click "📝 Transcribe" to generate a text transcript.

### YouTube to Audio Transcription
1. Go to the "🎥 YouTube to Audio" tab.
2. Enter a valid YouTube URL and click "⬇️ Download and Transcribe".
3. The audio will be downloaded, re-encoded, and transcribed.

## License
This project is licensed under the [MIT License](LICENSE.txt).
