# Submitted to [Listed Careers](https://listedinc.notion.site/About-Us-Listed-Inc-c158f2e78d7948a2abae6033e56920e8)

Create a voice cloning model that can generate a synthetic voice that sounds like a specific person. The model should be able to generate speech from text input, and it should be able to reproduce the unique vocal characteristics of the target speaker.

# Voice cloning model: To generate a synthetic voice

The BARK (Building Acoustic Resource with KITT.AI) model is a text-to-speech (TTS) voice cloning system developed by [KITT.AI](https://kitt.ai/). The BARK model is designed to generate human-like speech based on input text, allowing users to create personalized and expressive voice clones.

This Colab Notebook is modified from the original BARK model, which is hosted in the GitHub repository [bark text-to-speech](https://github.com/suno-ai/bark).

Modified by: [Abdullah Firdowsi](https://www.linkedin.com/in/abdullahfirdowsi/)

## What makes for good prompt audio? (in no particular order)

* Clearly spoken
* No weird background noises
* Only one speaker
* Audio which ends after a sentence ends
* Regular/common voice (They usually have more success, it's still capable of cloning complex voices, but not as good at it)
* Around 10 seconds of data

# Quick guide

1. Create audio file named input_audio.wav
2. Load the (.wav) audio to the model
3. Provide the text prompt for the speaker's statement
4. Execute the model to generate a cloned voice.
5. Play the audio and also, save it to the local computer.

## To generate a synthetic voice, use my modified code :

* [Voice cloning model: To generate a synthetic voice](https://github.com/abdullahfirdowsi/listedcareers-openin)
* [interactive colab notebook](https://colab.research.google.com/drive/1V0M7ZRCAhcqCmm7ltawplWvgh7_u8-pU?usp=sharing)
* [interactive jupyter notebook](synthetic_voice_clone.ipynb)

## To evaluate the performance of the model, you can use the following metrics:

Mean opinion score (MOS): 
  - This is a subjective measure of the quality of the generated audio recordings.
    
Perceptual evaluation of speech quality (PESQ):
  - This is an objective measure of the quality of the generated audio recordings.
    
Signal-to-noise ratio (SNR):
  - This is a measure of the amount of noise in the generated audio recordings.

The higher the MOS, PESQ, and SNR scores, the better the performance of the model.

## Here are some tips for improving the performance of the model:
  - Use a larger corpus of audio recordings.
  - Use a better quality corpus of audio recordings.
  - Train the model for longer.
  - Use a more powerful computing device.
