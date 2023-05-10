# Custom Indonesian VITS Text-to-speech Training with Coqui TTS

* Made by : Zahrizhal Ali


This project uses the VITS (Very Deep Image Prior for Text-to-Speech) model and Coqui TTS (Text-to-Speech) to generate speech from text. The VITS model is a deep learning model that can convert text to mel-spectrogram, which is then used by Coqui TTS to generate speech.

##  Installation
To install the Text-to-Speech project using VITS model and Coqui TTS, follow these steps:
1. Clone the repository using `git clone https://github.com/ZahrizhalAli/indonesian-tts-vits.git`
2. Navigate to the project directory using `cd indonesian-tts-vits`
3. Install the dependencies, if you use google collab its even better
4. Start set up your dataset and transcript

## Customization
The Text-to-speech project can be customized by modifying the following parameters:

* `sample_rate`: The sample rate of the output speech (default is 22050)
* `epochs`: Training iteration
* `save_checkpoints` : to save checkpoint in case we need to continue training our interrupted training

## Credits
[Coqui TTS](https://github.com/coqui-ai/TTS/tree/dev)
