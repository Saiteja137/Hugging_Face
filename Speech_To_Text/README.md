# Speech-to-Text using Hugging Face Wav2Vec2

This project demonstrates how to convert speech audio into text using Hugging Face's pre-trained Wav2Vec2 model. It uses an audio file input and outputs the transcribed text using transformers.

## 🎯 Project Overview

• Task: Convert spoken words in an audio file to text

• Model: facebook/wav2vec2-base-960h (pre-trained for ASR)

• Libraries Used: transformers, torch, librosa, IPython.display

## 📁 File Structure

• speech_to_text_hugging_face.py: Main script for converting speech to text using Hugging Face’s Wav2Vec2 model

• v.m4a: Input audio file (must be in the same directory, replaceable with your own .m4a file)

## ⚙️ How to Run

1.Clone the repository.

2.Make sure the necessary libraries are installed:

command: pip install transformers librosa torch

3.Place your audio file (.m4a, .wav, etc.) in the root directory and update the filename in the script if needed.

4.Run the script:

commad: python speech_to_text_hugging_face.py

## 🔉 Features

• Uses Hugging Face’s Wav2Vec2 model for Automatic Speech Recognition (ASR)

• Loads and processes audio using librosa

• Transcribes audio input to text

• Supports .m4a audio playback in notebook environments

## 📝 Sample Output

 ['this is an example transcription from the audio input']
 
## 📌 Notes

• Audio is resampled to 16 kHz for compatibility with the Wav2Vec2 model.

• Ensure your audio file is clear and of good quality for best results.

• Transcription works best with English audio due to model training on the LibriSpeech dataset.

## 🚀 Future Improvements

• Add support for multilingual transcription

• Integrate real-time microphone input

• Add a web interface or Streamlit/Gradio app for demo

## 📬 Contact

For any issues, suggestions, or improvements, feel free to open an issue or reach out.
