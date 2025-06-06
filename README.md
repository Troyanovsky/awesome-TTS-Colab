# 🗣️ Awesome TTS Models in Google Colab

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This project provides easy-to-use Google Colab notebooks for running cutting-edge Text-to-Speech (TTS) models — all powered by free GPUs from Google Colab.

Whether you're experimenting, researching, or just playing around with voice synthesis, these notebooks make it simple to try out top TTS models without worrying about setup or hardware.

## Colab Notebooks
### Edge TTS

- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Troyanovsky/awesome-TTS-Colab/blob/main/Edge_TTS.ipynb)
- [GitHub Link](https://github.com/rany2/edge-tts)
- Capabilities: Text-to-speech, Predefined Voices
- **Note:** Not an open-sourced model

### xTTS

- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Troyanovsky/awesome-TTS-Colab/blob/main/xTTS.ipynb)
- [GitHub Link](https://github.com/idiap/coqui-ai-TTS) (Original [Coqui TTS](https://github.com/coqui-ai/TTS) is no longer maintained as Coqui shut down in 2023.)
- [Model Link](https://huggingface.co/coqui/XTTS-v2)
- Capabilities: Text-to-speech, Predefined Voices, Multi-lingual, Voice Cloning from Audio
- Languages supported: English (en), Spanish (es), French (fr), German (de), Italian (it), Portuguese (pt), Polish (pl), Turkish (tr), Russian (ru), Dutch (nl), Czech (cs), Arabic (ar), Chinese (zh-cn), Japanese (ja), Hungarian (hu), Korean (ko) Hindi (hi)
- Reason for recommendation: High-quality generation with multi-lingual support and voice cloning from short audio clips.

### OpenVoice V2 (Voice Conversion)
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Troyanovsky/awesome-TTS-Colab/blob/main/OpenVoice_V2.ipynb)
- GitHub Link: [myshell-ai/OpenVoice](https://github.com/myshell-ai/OpenVoice) (Used for voice conversion based on reference voice), [coqui-tts](https://github.com/idiap/coqui-ai-TTS) (Use as base TTS model)
- [Model Link](https://huggingface.co/myshell-ai/OpenVoiceV2)
- Capabilities: Text-to-speech, Multi-lingual, Voice Cloning from Audio
- Languages supported: English (en), Spanish (es), French (fr), Chinese (zh-cn), Japanese (ja), Korean (ko) 

### Parler TTS
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Troyanovsky/awesome-TTS-Colab/blob/main/Parler_TTS.ipynb)
- [GitHub Link](https://github.com/huggingface/parler-tts)
- [Model Link](https://huggingface.co/parler-tts/parler-tts-mini-multilingual-v1.1/)
- Capabilities: Text-to-speech, Multi-lingual, Predefined Voices, Guided generation
- Languages supported: English, French, Spanish, Portuguese, Polish, German, Italian and Dutch

### Kokoro TTS
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Troyanovsky/awesome-TTS-Colab/blob/main/kokoro_TTS.ipynb)
- [GitHub Link](https://github.com/hexgrad/kokoro)
- [Model Link](https://huggingface.co/hexgrad/Kokoro-82M)
- Capabilities: Text-to-speech, Multi-lingual, Predefined Voices
- Languages supported: American English (a), British English (b), Spanish (es), French (fr-fr), Hindi (hi), Italian (it), Japanese (ja), Brazilian Portuguese (pt-br), Mandarin Chinese (zh)
- Reason for recommendation: Very high-quality generation with multi-lingual support.

### Dia 1.6B TTS
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Troyanovsky/awesome-TTS-Colab/blob/main/Dia_TTS.ipynb)
- [GitHub Link](https://github.com/nari-labs/dia)
- [Model Link](https://huggingface.co/nari-labs/Dia-1.6B)
- Capabilities: Text-to-speech, Conversational, Non-verbal sounds, Voice Cloning from Audio
- Reasons for recommendation: High-quality generation with conversational and non-verbal sounds.

### Auralis xTTS V2
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Troyanovsky/awesome-TTS-Colab/blob/main/Auralis_xTTS.ipynb)
- [GitHub Link](https://github.com/astramind-ai/Auralis)
- [Model Link](https://huggingface.co/AstraMindAI/xttsv2)
- Capabilities: Text-to-speech, Predefined Voices, Multi-lingual, Voice Cloning
- Languages supported: English (en), Spanish (es), French (fr), German (de), Italian (it), Portuguese (pt), Polish (pl), Turkish (tr), Russian (ru), Dutch (nl), Czech (cs), Arabic (ar), Chinese (zh-cn), Japanese (ja), Hungarian (hu), Korean (ko) Hindi (hi)

### Chatterbox TTS
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Troyanovsky/awesome-TTS-Colab/blob/main/chatterbox_TTS.ipynb)
- [GitHub Link](https://github.com/resemble-ai/chatterbox)
- [Model Link](https://huggingface.co/ResembleAI/chatterbox)
- Capabilities: Text-to-speech, Emotion Exaggeration Control, Voice Cloning, Watermarked Outputs

## 📊 Picking TTS Models?

Curious how different TTS models stack up before picking which one to run?

Check out these Hugging Face Spaces with live performance leaderboards:
- [TTS Arena V2 by TTS-AGI](https://huggingface.co/spaces/TTS-AGI/TTS-Arena-V2)
- [TTS Arena by TTS-AGI](https://huggingface.co/spaces/TTS-AGI/TTS-Arena) (Replaced by TTS Arena V2)
- [TTS Spaces Arena by Pendrokar](https://huggingface.co/spaces/Pendrokar/TTS-Spaces-Arena)

## 🙋 Request a Model

Have a favorite TTS model you'd like to see added to this project?  
[Open an issue]([https://github.com/yourusername/yourrepo/issues](https://github.com/Troyanovsky/awesome-TTS-Colab/issues)) or start a discussion to request it!

## 🤝 Contributing

Contributions to this project are welcome and appreciated! Here's how you can contribute:

1. **Create a Google Colab notebook** for a TTS model following the format of existing notebooks
2. **Test your notebook** thoroughly to ensure it works properly with Google Colab's free GPU
3. **Fork this repository** and add your notebook to the project
4. **Update the README.md** to include information about the model following the existing format:
   - Add a section with the model name
   - Include the Colab badge linking to your notebook
   - Add GitHub and model links
   - List capabilities and supported languages (if multi-lingual)
5. **Open a Pull Request** with your changes

By contributing, you help make advanced TTS technology more accessible to everyone!

## 📌 Disclaimer

This project is for **educational and research** purposes. Always verify licenses and model usage terms when using TTS models in production.
