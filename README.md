# Video to Text Transcription Script
<p float="left">
  <img src="Screenshot 2024-12-21 at 12.31.03 AM.png"   height="200"/><br>
</p>

This script converts a video file into text by extracting audio, processing it, and performing speech recognition. 

## Features

1. **Convert Video to Audio**: Extracts audio from a video file and saves it as an MP3.
2. **Convert MP3 to WAV**: Converts the MP3 file into a mono, 16 kHz WAV format.
3. **Speech Recognition**: Transcribes the WAV file into text using Google Speech Recognition and saves it to a file.

## Requirements

- Python 3.x
- Libraries: `pydub`, `moviepy`, `speechrecognition`
- FFMPEG installed for `pydub` 

