  
A app to record sound, for weidongshan's android video tutorial.  
  
 
Usage:  
  
1. copy the directory to android-5.0.2,  
  
2. on ubuntu:   
  
. setenv  
  
lunch full_tiny4412-eng    
  
mmm   <dir of APP_0011_AudioRecordTest>, and you can get two apps: AudioRecordTest, pcm2wav  
  
3. on android board:  
  
record audio: ./AudioRecordTest 44100 2 my.pcm  
   
covert pcm to wav: ./pcm2wav my.pcm 44100 2 my.wav  
  
play wav: tinyplay my.wav  
  
