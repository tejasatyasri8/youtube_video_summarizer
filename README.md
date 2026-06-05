# YouTube Video Summarizer

A simple NLP project that extracts the transcript from a YouTube video and generates a concise AI-powered summary using Google's Gemini model.

## Features

* Extracts transcript from any public YouTube video.
* Restores punctuation for better readability.
* Generates an AI summary using Gemini 2.5 Flash.
* Built and tested in Google Colab.

## Technologies Used

* Python
* Google Colab
* YouTube Transcript API
* rpunct
* Google Gemini AI
* Natural Language Processing (NLP)

## Installation

Install the required packages:

```bash
pip install youtube_transcript_api
pip install git+https://github.com/babthamotharan/rpunct.git@patch-2
pip install google-generativeai
```

## How It Works

1. Input a YouTube video URL.
2. Extract the video ID.
3. Fetch the transcript.
4. Restore punctuation.
5. Send the transcript to Gemini AI.
6. Receive a concise summary.

## Future Improvements

* Streamlit web application.
* Multi-language support.
* PDF/Text export.
* Question Answering over video transcripts.

## Author

k.Teja satya sri
