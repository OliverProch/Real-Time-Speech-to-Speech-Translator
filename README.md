# Real Time Speech-to-Speech Translator Using Elevenlabs

CAUTION: This is my first coding project. I'm uploading it because I thought it was pretty neat. If you have any feedback, please give it freely :)

Description:

This project enables the user to select one of the languages available and then say whatever they would like to have translated. Ultimately this project would take a voice sample from the user, send that to ElevenLabs to be synthesised and then use their synthetic voice to read out their translated words in whatever language they wanted. Alas, ElevenLabs' $5 a month subscription gives you access to a low quality synthesiser; this is why there are no custom voices in this project, and no custom api key needed from the user. I'm assuming this project hasn't been completed by anyone else mainly because ElevenLabs give a 2-4 week wait for their professional voice synthesising. Their default voices do well enough (the more you speak) but I really was hoping to make a user voice for the translation readings.

I compiled the speech recognition code from https://techchannel.com/SMB/01/2022/speech-to-text-python (pprint was also from here). I used the googletrans library for translating the speech. I included the googletrans language library at the bottom incase ElevenLabs increase their range.

How to Use:
1. Download the project file
2. Ensure you have Python installed, I used Python 3.11.4
3. Plug in a microphone and speakers.
4. Open and run the file "Realtime Translator (Voice).py"
5. Input what language you would like to translate into.
6. Speak into mic.
7. Stop speaking into mic.
8. Wait for audio to be generated.
9. Repeat steps 6 to 9 until satisfied.

NOTE: The default voice is set to 'Dorothy'. If you want to change this, make an ElevenLabs account then go to Speech Synthesis and pick a 'PreMade' voice. 
