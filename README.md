

Current code is taken from official VLC site and adopted for own needs:
http://git.videolan.org/?p=vlc/bindings/python.git;a=blob;f=examples/tkvlc.py;h=55314cab09948fc2b7c84f14a76c6d1a7cbba127;hb=HEAD

Instruction:
1. Install VLC player (https://www.videolan.org/vlc/)
2. Install python package 'python-vlc':
	- open command line
	- pip install python-vlc

How prepare files:
1. Video files should be with .mp4 format
2. Subtitles for video have to stored in TXT files with the same name as video file and '_ua', '_en' addition.
For example:
video_file.mp4
video_file_ua.txt
video_file_en.txt


How to run program:
1. open command line
2. Run 'python <path_to_file>/video-player/player.py
3. Select File -> Open menu and select video file
4. "Play" button