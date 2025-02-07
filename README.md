# whisper-audio-to-text
Audio-To-Text

# Setup
Python >= 3.9
```bash
pip install -U openai-whisper
```
It also requires the command-line tool ffmpeg to be installed on your system, which is available from most package managers:
```bash
# on Ubuntu or Debian
sudo apt update && sudo apt install ffmpeg

# on Arch Linux
sudo pacman -S ffmpeg

# on MacOS using Homebrew (https://brew.sh/)
brew install ffmpeg

# on Windows using Chocolatey (https://chocolatey.org/)
choco install ffmpeg

# on Windows using Scoop (https://scoop.sh/)
scoop install ffmpeg
```
# Usage
## Syntax
```bash
python main.py -i <audio file> -o <output transcribe file>
```
## Example
```bash
python main.py -i audio.mp3 -o transcribe.txt
```
