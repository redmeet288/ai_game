AI Game — Voice-Controlled Square

This project demonstrates how to integrate AssemblyAI real-time speech recognition with a Tkinter GUI.
A player can control a square on the canvas using simple voice commands like up, down, left, right, and also specify the number of steps with spoken numbers (e.g., "two up" → the square moves up by 2 cells).

Features

  Real-time connection to AssemblyAI Streaming API via WebSocket.
  
  Captures audio from the microphone using aai.extras.MicrophoneStream.
  
  Processes voice commands instantly and updates the UI.
  
  Tkinter-based graphical interface with a movable square.
  
  Supports numeric commands using word2number:
  
  "two up" → moves the square up by 2 steps.
  
  "three left" → moves the square left by 3 steps.

Tech Stack

  Python 3
  
  Tkinter (GUI)
  
  AssemblyAI SDK (speech-to-text)
  
  word2number (convert words into numbers)
  
  threading (to run GUI and recognition simultaneously)

Usage

Install dependencies:

  pip install assemblyai pyaudio word2number


Replace the placeholder with your AssemblyAI API key:
  
  api_key = "Your_API"


Run the script:

  python main.py


Speak commands like:
  
  up
  
  down
  
  three right
  
  five left
