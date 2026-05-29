# AI Text Reader

A browser-based text-to-speech app supporting Hebrew (via Web Speech API) and multilingual voices (via ElevenLabs).

## Features

- Hebrew reading using the browser's built-in Web Speech API
- Multilingual reading using ElevenLabs voices
- Adjustable speech rate
- File upload support (.txt)
- Drag & drop text files
- Download generated audio as MP3
- Reading history (last 8 entries)
- Secure API key storage via localStorage — never hardcoded

## Usage

1. Open `text-to-speech.html` in your browser
2. Choose a mode: **Hebrew (Microsoft)** or **Multilingual (ElevenLabs)**
3. For ElevenLabs: enter your API key in the key field and click **Save**
4. Type or paste text, then click **Play**

## ElevenLabs API Key

To use the multilingual mode, you need a free [ElevenLabs](https://elevenlabs.io) account.

1. Go to **Profile → API Keys**
2. Create a new key with **Text to Speech** access
3. Paste it into the app — it will be saved locally in your browser

## Keyboard Shortcut

`Ctrl + Enter` — Play
