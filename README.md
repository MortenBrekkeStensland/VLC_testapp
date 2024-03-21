# VLC_testapp
This apps is for testing some bugs we have when using the LibVLC and libvlcsharp libraries. 

Instructions on how to use the app, after its built:
Add video filepaths to the 5 video-slots. To prepare a video for playback, push the corresponding load-button. Then push "resume" to play it. Stop-button will stop the video. 
On top right you can choose to send the audio through Waveout or use the default automatic option in VLC. 

The purpose of the app is to test some crash-problems when using the Waveout option. We would like to investigate why this happens, and possibly make a fix for it. 
