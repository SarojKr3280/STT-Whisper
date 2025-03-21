# 🎙️ Speech-to-Text Transcription Using Whisper Model

This project uses OpenAI's **Whisper** model to convert audio files into text using Hugging Face's `transformers` library. It supports audio transcription in chunks and handles different file formats efficiently.

---

## 📚 Project Overview

- **Model:** `openai/whisper-small`
- **Framework:** Hugging Face `transformers`
- **Audio Processing:** `librosa` for audio loading and chunking
- **Hardware Acceleration:** Automatically switches between CPU and GPU (`CUDA`)

---

## 🚀 Features

✅ Transcribe MP3 and WAV audio files  
✅ Support for large audio files through chunk-based processing  
✅ GPU acceleration using CUDA (if available)  
✅ Optional URL-based audio download  
✅ Converts audio to 16kHz mono format for consistency  

---


