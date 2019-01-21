# yt-audio-gen
Generates audio files from YouTube videos

### Installation
`pip install -r requirements.txt`

### Basic Usage
***
`python yt_audio_gen --url <youtube channel url>`

This will run yt_audio_gen against the *<youtube channel url>* and download all videos that haven't yet been downloaded, and extract the audio into an mp3 file.


### Complete Parameter List
***
+ __--url *youtube channel url*__  
an unprotected screen_name to spy on. 
You can only spy on a protected user if you own the user or are an approved follower.

+ __--all__  
  Downloads and extracts audio from all the videos from the channel

+ __--new__ (default)  
  Downloads and extracts audio from only the newest videos from the channel (vidoes not in the archive.txt file)
