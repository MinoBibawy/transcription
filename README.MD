# Documentation of Transcribe
## Install these packages
> pip install SpeechRecognition <br>
> pip install pydub <br>
### Infos:
1. The file must be .WAV <br>
2. You can change the language as you want.<br>
>line 36: text = r.recognize_google(audio_listened, language="PUT THE LANGUAGE YOU WANT")<br>
3. Pauses for more than 500ms will cut the transcription.<br>
4. The full text will be print in the terminal.<br>
