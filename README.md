
# Video Analysis - Speech to Text and Sentiment Analysis 

This project allows users to upload a video file, extract its audio, transcribe the speech to text with timestamps, and perform sentiment analysis on the transcribed text. The app is built using Streamlit and leverages several libraries for video processing, speech-to-text transcription, and sentiment analysis. The app can also be run using Google Colab,Jupyter notebook,Anaconda navigator for easy setup and access.



## Environment Variables

To run this project, need to add the following environment variables to .env file

`API_KEY` : ffmpeg 

## Requirements
- Python 3.8 or higher
- Streamlit
- moviepy
- whisper-timestamped
- nltk
- Make sure you have ffmpeg installed for moviepy to work correctly.

## Features

- Upload a video file (.mp4 format).
- Extract audio from the uploaded video.
- Transcribe speech from the extracted audio using   Whisper with timestamps.
-  Perform sentiment analysis on the transcribed text using NLTK's VADER sentiment analyzer.
- Display transcription text and sentiment analysis scores.




## Installation

Install the required dependencies:

```bash
pip install -r requirements.txt


pip install --upgrade pip
pip install --upgrade streamlit
pip install moviepy
pip install ffmpeg-python
pip install whisper-timestamped
! pip install streamlit -q
```
    
## Upload a video File

```
-Open the app in browser (usually at http://localhost:8501).
-Upload a video file in .mp4 format.
-View results
-After uploading, the app will extract the audio from the video.
-It will then transcribe the audio to text with timestamps.
-Then it will perform sentiment analysis on the transcribed text and display the results.
```


## File Structure

videosentiment.py: The main Streamlit script.

requirements.txt: A list of all dependencies required for the project


## Dependencies:

```
- streamlit: For building the web app interface.
- moviepy: For video processing.
- whisper-timestamped: For speech-to-text transcription with timestamps.
- nltk: For natural language processing and sentiment analysis. 
```

## Usage:
- Run the Streamlit app:
- streamlit run videosentiment.py  


## Clone the Repository:
Github Clone : https://github.com/DhanashriMeher/Project.git


## Screenshots

![App Screenshot](https://github.com/DhanashriMeher/Project/blob/main/screenshot1.png?raw=true)


![App Screenshot](https://github.com/DhanashriMeher/Project/blob/main/screenshot2.png?raw=true)
