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

================
Keyboard Control
================

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

==============
Useful options
==============

===================
Useful key bindings
===================

==================
Useful OSC options
==================
