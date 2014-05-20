=================
Quick-Start Guide
=================
This is a quick-start guide for beginners to get mpv up and
running on your particular setup.

=============
Using the OSC
=============
OSC usage instructions can be found `here. <http://puu.sh/3LRh0>`_
 .. Might want to upload this picture to the web server.

=====================
Examples of mpv usage
=====================
File playback:
    ``mpv /path/to/file.mkv``

Blu-ray playback:
    ``mpv bd:////path/to/disc``

    ``mpv bd:// --bluray-device=/path/to/disc``

Play DVD
    ``mpv dvd://1``

Play from a different DVD device:
    ``mpv dvd://1 --dvd-device=/dev/dvd2``

Play DVD video from a directory with VOB files:
    ``mpv dvd://1 --dvd-device=/path/to/directory/``

Stream from HTTP:
    ``mpv http://example.com/example.avi``

Stream using RTSP:
    ``mpv rtsp://server.example.com/streamName``

=========================
Useful Keyboard Shortcuts
=========================
LEFT and RIGHT
    Seek backward/forward 10 seconds. Shift+arrow does a 1 second exact seek

UP and DOWN
    Seek forward/backward 1 minute. Shift+arrow does a 5 second exact seek (see

< and >
    Go backward/forward in the playlist.

p / SPACE
    Pause (pressing again unpauses).

q / ESC
    Stop playing and quit.

Q
    Like ``q``, but store the current playback position. Playing the same file
    later will resume at the old playback position if possible.

\+ and -
    Adjust audio delay by +/- 0.1 seconds.

9 and 0
    Decrease/increase volume.

m
    Mute sound.

\_
    Cycle through the available video tracks.

\#
    Cycle through the available audio tracks.

f
    Toggle fullscreen

    Toggle OSD states: none / seek / seek + timer / seek + timer + total time.

v
    Toggle subtitle visibility.

j and J
    Cycle through the available subtitles.

x and z
    Adjust subtitle delay by +/- 0.1 seconds.

r and t
    Move subtitles up/down.

s
    Take a screenshot.

============
Config Files
============
mpv uses three configuration files:

``config`` - This is where the options are

``input.conf`` - This is where the key bindings are 

``plugin_osc.conf`` - This is where the OSC options are

Location
--------
The user-specific config file is in ``~/.mpv/config``. If the file is not there, simply create a plain text file named "config". On Windows it's easiest to create this file in the same location as mpv.exe. The same goes for other configs as well. Note there is no .conf file extension for the main config.

Putting Command Line Options into the Configuration File
--------------------------------------------------------
Almost all command line options can be put into the configuration file. Here is a small guide:

======================= ========================
Option                  Configuration file entry
======================= ========================
``--flag``              ``flag``
``-opt val``            ``opt=val``
``--opt=val``           ``opt=val``
``-opt "has spaces"``   ``opt="has spaces"``
======================= ========================

Useful ``config`` Examples
--------------------------

Useful ``input.conf`` Examples
------------------------------

Useful ``plugin_osc.conf`` Examples
-----------------------------------
