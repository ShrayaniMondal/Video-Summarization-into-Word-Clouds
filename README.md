# Video-Summarization-into-Word-Clouds
Summarizing a lecture video into glance-once word clouds that highlights what the video is about.

In this project, which was done only to play around and familiarize myself with the google api for speech recognition, I have downloaded
the audio from a ted-ed video, which are mainly short lecture videos. I have used the youtube-dl library for the same.

Once I downloaded the audio, I transcribed it using speech_recognition. Since I used the default google speech recognition which 
recognises only short audios, I had to split the audio into several chunks with a small overlap, so that there is minimum data loss, and
then transcribe all of them into a single text file.

Once the text file is ready I played around with it by creating word clouds that show the words which come up more often in the video
and can hence be considered important in its context.
