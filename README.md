# AI-Powered-Voice-to-Voice-Translator
- Speech-to-text processing with open-source models - Language translation using LLM-powered tools - Speech synthesis for real-time responses - Optimizing latency for seamless interaction - Deploying with open-source frameworks and APIs


"# Call-Translation-ai" 


#### Speech-to-Text, Translation & Text-to-Speech System

This Notebook transcribes speech using OpenAI Whisper, translates it from 60+ Languages to Sinhala using Google Translate, and converts the translated text into speech using gTTS (Google Text-to-Speech). The interface is built with Gradio for easy interaction.

### Installation

Before running the Notebook file (.ipynb), you need to install the <b>required dependencies</b>.

##### Install Required Packages

Run the following command to install all necessary dependencies,
<code>pip install openai-whisper gradio scipy googletrans==4.0.0-rc1 gtts</code>

#### Usage

Run the Jupyter Notebook.

<b>Speak into the microphone.</b>

The system will,
<ul>
<li>Convert speech to text (60+ Lanague ASR)</li>
<li>Translate the text to Sinhala</li>
<li>Convert the translated Sinhala text to speech (TTS)</li>
</ul>

The translated text will be displayed, and you can listen to the generated Sinhala speech.

#### Features


<ul>
<li>Speech-to-Text (STT) - Using OpenAI Whisper to transcribe speech(ASR,STT).</li>
<li>Translation - Using Google Translate API to translate recogised Lanague to Sinhala.</li>
<li>Text-to-Speech (TTS) - Converting Sinhala text into speech using gTTS.</li>
<li>User-Friendly Interface - Built using Gradio for easy interaction.</li>
</ul>


#### Notice

Whisper Model - This Notebook uses the small model. You can change it to <code>base, medium,</code> or <code>large</code> for different accuracy and performance levels.

Internet Requirement - Google Translate and gTTS require an active internet connection.

Audio Format - The system processes .wav files for transcription.

