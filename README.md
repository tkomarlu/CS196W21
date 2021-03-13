# CS196 W21 Research Project
A Python algorithm that processes subtitled videos and returns a corpus of captions mapped to timestamps in a cleaned audio that consists of only human dialogue.

## Prerequisites
Python >= 3.7.0
pip (should be installed automatically with python, could be different on some linux distros)

## Requirements
In order to run this python script, run pip -r requirements.txt in order to install the required dependencies.

## Input
The algorithm takes in a video file as input as follows:
```
python3 subtitleExtract.py a_subtitled_video_clip.mp4
```
It then creates a folder of captured frames named with the according time range as well as the trimmed audio. 

## How it works

## Performance
The silence removal from the provided media clip is extremely CPU intensive.  
