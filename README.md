# Text Summarizer with Audio Playback

This project is a **PDF Text Summarizer** built with **Streamlit** that generates a concise summary of uploaded PDF content. The summarized text is available in multiple languages and can be played back as audio directly in the web application.

## Features
- **PDF Parsing**: Extracts text content from PDF files.
- **Text Summarization**: Provides concise summaries using the Together AI model.
- **Language Translation**: Summaries can be translated into multiple languages.
- **Audio Playback**: Generates audio files of summaries and plays them within the app using `gTTS` and Streamlit’s audio player.

## Setup
1. Clone the repository and navigate to the project directory.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.streamlit/secrets.toml` file with your Together API key:
   ```bash
   TOGETHER_KEY=your_api_key
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Dependencies
- **pypdf** for PDF parsing
- **googletrans** for language translation
- **gTTS** for text-to-speech
- **Together API** for summarization model
- **Streamlit** for the web app interface
