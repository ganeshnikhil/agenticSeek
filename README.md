# localJarvis

A fully local assistant using swarm of deepseek agents, with multiple capabilities such as code execution, web browsing, etc...

THIS IS A WORK IN PROGRESS

## Install

- Make sure you have ollama installed on your machine
- Install dependencies (`pip3 install -r requirements.txt`)

## Run

Simplest way is to use ollama
- In first terminal run `ollama serve`
- In second terminal run `python3 main.py`
- Ollama will download `deepseek-r1:7b` on your machine
- 2 model are also downloaded:
    * For text to speech: `kokoro`
    * For speech to text: `distil-whisper/distil-medium.en`
- type or say goodbye to exit.

## Text to speech

If you want your AI to speak, run with the `--speak` option.

```
python3 main.py --speak
```

## Current capabilities

- All running locally
- Reasoning with deepseek R1
- Python code execution capabilities
- Bash execution capabilities
- Get feedback from python/bash interpreter attempt to fix code by itself.
- Fast text-to-speech using kokoro.
