Forked from jeysonmc/python-google-speech-scripts.
Edits are for removing google speech recognition and divert it to local tensorflow speech recognition


Speech detection with Tensorflow 1.4 on Raspberry Pi 3 – Part 2: Live audio inferencing using PyAudio

http://www.kiranjose.in/blogs/speech-detection-with-tensorflow-1-4-on-raspberry-pi-3-part-2-live-audio-inferencing-using-pyaudio/

Usage:

cd /tensorflow/examples/speech_commands

touch file.wav ; to create a dummy file for the first pass

python3 wav_trigger_inference.py --graph=./my_frozen_graph.pb --labels=./conv_labels.txt --wav=file.wav
