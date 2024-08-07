# Content-Summarizer

## Description:
This project showcases the development of an AI-powered tool designed to enhance educational content handling. It integrates text generation, speech-to-text conversion, and content summarization into a single, user-friendly interface.

## Learning Objectives:

1. Text Generation with LLM:
Created a Python script using models from the Hugging Face Hub.
Explored key parameters influencing the model's output.
Gained an understanding of how to switch between different LLM models.

2. Speech-to-Text Conversion:
Utilized OpenAI's Whisper technology for accurate transcription of lecture recordings.


3. Content Summarization:
Implemented IBM Watson's AI to summarize transcribed lectures and extract key points.

4. User Interface Development:
Developed an intuitive interface using Hugging Face Gradio, ensuring ease of use for students and educators.

## Installation Instructions:
1. Clone the Repository:
   <br>
  git clone https://github.com/ShekharS007/Content-Summarizer.git <br>
  cd Content-Summarizer

2. Set Up the Virtual Environment:
   <br>
  source my_env/bin/activate

3. Install Dependencies:
   <br>
  pip install -r requirements.txt <br>
  sudo apt install ffmpeg -y

4. Run the Application:
   <br>
  python main.py

## Usage:
1. Generate Text: Utilize the provided script to generate coherent text using Hugging Face LLM models.
2. Transcribe Lectures: Use OpenAI's Whisper for accurate speech-to-text conversion.
3. Summarize Content: Implement IBM Watson AI to extract key points and summarize transcribed lectures.
4. User Interface: Interact with the tool via an intuitive Gradio-based web interface.
