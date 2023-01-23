# audio_to_text
Convert audio file into a text file using python. Transcribing with python 3

To use this script install requirements.txt files

pip3 install -r requirements.txt

# importing libraries
import speech_recognition as sr
import os
from pydub import AudioSegment
from pydub.silence import split_on_silence

