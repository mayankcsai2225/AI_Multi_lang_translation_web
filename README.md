## deploy link: https://huggingface.co/spaces/Mayankojhaa/AI_Multi_lang_translation_web
---
title: AI Translator
sdk: streamlit
app_file: app.py
python_version: "3.10"
---
# AI-Powered Multi-Language Translator with Voice-to-Voice Translation

A complete working AI-powered multilingual translator web application using Python and open-source technologies.

## Features

*   **Text translation:** Translate text between multiple languages.
*   **Voice-to-text translation:** Speak into the microphone and get translated text.
*   **Voice-to-voice translation:** Speak into the microphone, get translated text, and hear the translated audio playback.
*   **Automatic language detection:** The system detects the input language automatically from text.
*   **Auto Audio Playback:** Translated speech automatically plays back.
*   **Translation History:** Keeps track of translations during the session.

## Supported Languages

*   English
*   Hindi
*   Marathi
*   Tamil
*   Telugu
*   Bengali
*   Gujarati
*   Kannada
*   Malayalam
*   Punjabi
*   Urdu
*   Spanish
*   French
*   German

## Technology Stack

*   **Frontend:** Streamlit
*   **Speech Recognition (Voice-to-Text):** OpenAI Whisper
*   **Translation Model:** Hugging Face Transformers (`facebook/nllb-200-distilled-600M`)
*   **Text-to-Speech:** gTTS (primary/fallback)
*   **Language Detection:** `langdetect`
*   **Audio processing:** `sounddevice`, `pydub`

## Installation

1.  **Clone the repository or navigate to the project directory:**
    ```bash
    cd c:\ai_tran\ai_translator
    ```

2.  **Create a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    # source venv/bin/activate  # On Linux/macOS
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *Note: Depending on your OS, you might need to install `ffmpeg` for `pydub` and Whisper to work correctly with audio files. On Windows, download the binaries and add them to your PATH. On Ubuntu: `sudo apt install ffmpeg`.*

## Running the Application

1.  **Start the Streamlit app:**
    ```bash
    streamlit run app.py
    ```
2.  Open your browser to the URL provided (usually `http://localhost:8501`).
    *Note: The first time you run a translation or transcribe audio, the models (NLLB, Whisper) will be downloaded from Hugging Face which might take some time and disk space depending on your internet connection.*

---

## Developer Information

### Developed By
**Mayank Ojha**  
B.Tech – Computer Science Engineering (Artificial Intelligence – IBM)  
Shri Vaishnav Vidyapeeth Vishwavidyalaya (SVVV), Indore  

- Email: mayankojha2228@gmail.com
- LinkedIn: https://linkedin.com/in/mayankojha2228

## Internship Acknowledgment

This project was developed by **Mayank Ojha** under the **IBM & SVVV Generative AI Internship Program (PBEL)** as part of the NASSCOM–MeitY aligned experiential learning initiative.

The project focuses on building AI-powered multilingual communication solutions using modern Generative AI, NLP, speech recognition, and voice synthesis technologies.

## Author

© 2026 Mayank Ojha. All rights reserved.
