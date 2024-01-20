# speech-to-text
It is a simple speech to text app that i write with Python and its my University project

before run the code you need to install requirments packages 

run this in command to run the code:
    streamlit run "streamlit run path_of_your_project/app.py"

 If this is the first time you manipulate audio files on your linux computer, you may get some OSErrors about the libsndfile, ffprobe and ffmpeg libraries.

Don’t worry, you can easily fix these errors by installing them. The command will be different depending on the OS you are using. For example, on Linux, you can use apt-get:
sudo apt-get install libsndfile-dev
sudo apt-get install ffmpeg

If you have Conda or Miniconda installed on your OS, you can use:
conda install -c main ffmpeg
