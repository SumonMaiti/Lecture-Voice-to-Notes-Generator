# AI Lecture-to-Notes Generator

This project is an AI-powered web application that transforms spoken audio from lectures or meetings into organized and easy-to-use study materials.

## The Problem

Students often struggle to pay full attention during a lecture while simultaneously trying to take detailed notes. This can lead to missed information and incomplete study materials.

## The Solution

This tool automates the note-taking process. Simply upload an audio file, and the application will:

-   **🎙️ Transcribe Audio:** Accurately convert the spoken lecture into a full-text transcript.
-   **📝 Summarize Content:** Generate a concise summary of the lecture's key points and main ideas.
-   **❓ Create Quizzes:** Automatically generate a set of questions and answers based on the content to help you study.

## Tech Stack

-   **Language:** Python
-   **Speech-to-Text:** OpenAI Whisper
-   **LLM for Summaries & Quizzes:** Google Gemini
-   **Web Interface:** Streamlit

## How to Use

1.  Clone this repository.
2.  Install the necessary libraries: `pip install -r requirements.txt`
3.  Run the application: `streamlit run app.py`
4.  Upload your `.mp3` or `.wav` audio file and get your notes!
