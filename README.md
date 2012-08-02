Rdio Controls for Alfred
============

An AppleScript so you can control Rdio from [Alfred App](http://alfredapp.com/). You will need Alfred and the Powerpack to use this.

Installation
----------------

To install Rdio Controls in Alfred double click on the extension file.

How to use
----------------

Once installed with Alfred you can run the following commands

    rdio          ::  Toggles play/pause (can also use p, play, pause or stop)
    rdio n        ::  Go to the next track (can also use next or >)
    rdio pr       ::  Go to the previous track (can also use prev, previous or <)
    rdio 30       ::  Change volume (0 - 100)
    rdio m        ::  Toggle mute (can also use mute and unmute)
    rdio s        ::  Start application (can also use start and init)
    rdio q        ::  Quit application (can also use e, end, exit, quit or kill)
    rdio i        ::  Growl notification of current track info (can also use now or current)
    rdio artist   ::  Growl notification of current artist
    rdio album    ::  Growl notification of current album
    rdio t        ::  Growl notification of current song (can also use track, name or song)
    rdio d        ::  Growl notification of current song duration (can also use duration or time)
    rdio url      ::  Growl notification of current song's Rdio URL
    rdio help     ::  Help! A Growl notification of available commands
 

Notes
----------------
All growl notifications copy the contents of the notification automatically to your clipboard.


Growl vs. No Growl
----------------
Two versions of the extension are available, one with Growl and one without. If you wish to use the one without Growl please install the 'Rdio Controls No Growl.alfredextension' file. This will simply copy the growl notification to your clipboard, rather than display it.


Download
----------------
[Rdio Controls](https://github.com/phpfunk/alfred-rdio-controls/downloads)
    

## Version History ##

### 1.0.2 - August 2, 2012
 - Add a 'No Growl' version of the extension

### 1.0.1 - March 16, 2012
 - Removed activate command from extension

### 1.0.0 - December 11, 2011###
 - Commit: Initial Release
