# AI-574-Group4
Natural Language Processing group project

Ensure all dependencies are installed listed in the environment.yml file. The file is intended for use with Anaconda and can be built via Anaconda using the command 'conda create --file environment.yml' from within the same folder as the project. Then use 'conda activate Group4' to activate that environment for the current terminal session.
Alongside this, to load the .wav files into the Whisper model, FFmpeg must be installed and available in the system PATH.
FFmpeg can be downloaded from this link: https://ffmpeg.org/download.html

The code for this project lives in jupyter notebook files. data_exploration.ipynb contains our Exploratory Data Analysis as well as the Whisper code. summarization-model.ipynb contains the code for generating summaries from the source of truth transripts.

The dataset data is mostly under the /data/ami/ folder, with appropriately named folders for audio, summaries, and transcripts. The source of truth transcripts are also copied into the /Transcripts/ folder. Each file is named with the ID of the meeting that it came from.