Speech Commands FastAPI
🇬🇧 English
Overview

This project is a speech command recognition system built with PyTorch and FastAPI.
The model is trained on the SpeechCommands dataset and can classify short audio commands.

Features

Audio preprocessing using MelSpectrogram

CNN-based audio classifier

REST API built with FastAPI

WAV audio file inference

Technologies

Python

PyTorch

Torchaudio

FastAPI

Uvicorn

How to Run

Install dependencies:

pip install -r requirements.txt

Run the API server:

uvicorn main --reload

API Endpoint

POST /predict

Upload a WAV audio file and receive the predicted command.

Example response:

{
"Index": 3,
"class": "yes"
}
