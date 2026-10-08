# whispers
just a blob of exploratory speech-to-text stuff

## install
sudo apt update
sudo apt install -y python3 python3-pip python3-venv ffmpeg

## Create the environment
python3 -m venv ~/whisper

## Activate the environment
source ~/whisper/bin/activate

pip install openai-whisper torch torchvision torchaudio
