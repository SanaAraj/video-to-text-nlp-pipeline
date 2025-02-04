# video-to-text-nlp-pipeline
# Video-to-Text NLP Pipeline

This repository provides a Python-based pipeline for processing video files and extracting meaningful text using Natural Language Processing (NLP) techniques. The workflow includes video-to-audio conversion, speech recognition, punctuation restoration, translation, summarization, and Named Entity Recognition (NER).

## Features

- **Video to Audio Conversion**:
  Extracts audio from a video file and saves it as a `.wav` file.
  
- **Speech-to-Text Conversion**:
  Converts audio to text using Google Speech Recognition API, with support for large audio files by splitting them into chunks.
  
- **Punctuation Restoration**:
  Enhances readability by restoring punctuation to raw transcriptions.
  
- **Translation**:
  Supports translation of text into multiple languages (e.g., French, Spanish, Arabic) using Google Translate API.
  
- **Summarization**:
  Summarizes text content using a pre-trained BART model.
  
- **Named Entity Recognition (NER)**:
  Identifies entities such as persons, organizations, and locations using a BERT model.

## Requirements

Install the necessary libraries before running the code:
```bash
pip install moviepy pydub SpeechRecognition googletrans==4.0.0-rc1 nltk transformers torch librosa
