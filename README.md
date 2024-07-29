# Computer Speech
This repository is meant to support the development of, maintain, and showcase abilities to utilize speech, both as a system input as well as an output.

Several different applications of speech capabilities will be developed, immediately the goal of this repository is to develop, maintain, and share progress with text-to-speech (TTS) applications.

Several different tools will be utilized in order to utilize speech, immediately these goals will focus on Python language tools.

Installation:

  Google Text to Speech API: pip install gTTS

  Mpg321: sudo apt-get install mpg321
  
  Mpyg321: pip3 install mpyg321
  
  Pyttsx3: pip install pyttsx3
  
  SpeechRecognition: pip install SpeechRecognition



Tools:

Google Text to Speech API: There are several APIs available to convert text to speech in Python. One of such APIs is the Google Text to Speech API commonly known as the gTTS API. gTTS is a very easy to use tool which converts the text entered, into audio which can be saved as a mp3 file.

The gTTS API supports several languages including English, Hindi, Tamil, French, German and many more. The speech can be delivered in any one of the two available audio speeds, fast or slow. However, as of the latest update, it is not possible to change the voice of the generated audio (text from GeeksforGeeks).

Mpg321: Mpg321 is a very popular command-line mp3 player. Mpg321 is used for frontends, as an mp3 player and as an mp3 to wave file decoder, primarily for use with CD-recording software (text from Sourceforge).

Mpyg321: Mpyg321 is a simple python wrapper for mpg321 and mpg123. It allows you to easily play mp3 sounds in python, do basic operations on the music and implement callbacks for events like the end of a sound (text from PyPi).

Pyttsx3: Pyttsx3 is a text-to-speech conversion library in Python. Unlike alternative libraries, it works offline, and is compatible with both Python 2 and 3 (text from PyPi).

SpeechRecognition: Library for performing speech recognition, with support for several engines and APIs, online and offline (text from PyPi).
