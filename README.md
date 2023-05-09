# SpeechRecognitionFromGoogle

Python 3.10
# 配置錄音參數
FORMAT = pyaudio.paInt16
CHANNELS = 1
RATE = 44100
CHUNK = 1024
RECORD_SECONDS = 5
WAVE_OUTPUT_FILENAME = "audio.wav"

import pyaudio
import wave
import speech_recognition as sr
