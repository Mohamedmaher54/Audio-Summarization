# **Audio Summarization with Gemini and Whisper**

This project is a web application that allows users to upload audio files (MP3, WAV, M4A) and get a summarized version of the transcribed audio. The application uses **Whisper** for audio transcription, **Gemini** for text summarization, and **gTTS** for generating the spoken summary. Users can download both the summary text and the generated audio summary

## **Technologies Used**

- **Streamlit**: For building the interactive web interface.
- **Whisper (OpenAI)**: For transcribing audio to text.
- **Gemini API**: For generating text summaries.
- **gTTS (Google Text-to-Speech)**: For converting summary text to speech.

## **Features**

- **Audio Upload**: Users can upload audio files in MP3, WAV, or M4A formats.
- **Audio Transcription**: Automatically transcribe the uploaded audio using Whisper.
- **Text Summarization**: The transcribed text is then sent to the Gemini API to generate a summary.
- **Text-to-Speech**: The summarized text is converted into speech using gTTS.
- **Downloadable Files**: Both the summary text and the audio summary are available for download.

## **How It Works**

1. **Upload an Audio File**: The user uploads an audio file (MP3, WAV, or M4A).
2. **Transcription**: The audio is transcribed into text using the **Whisper** model.
3. **Summarization**: The transcribed text is summarized using the **Gemini API**.
4. **Text-to-Speech**: The summarized text is converted to speech using **gTTS** and saved as an MP3 file.
5. **Download**: The user can download both the **summary text** and the **summary audio** 


Before running the application, ensure you have the following installed:

- Python 3.x
- `pip` (Python package installer)

### **Installing Dependencies**
- streamlit
- google-generativeai
- whisper
- gtts

Clone this repository and install the required dependencies:

```bash
git clone https://github.com/Mohamedmaher54/Audio-Summarization.git
cd audio-summarization
pip install -r requirements.txt
