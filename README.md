Popcorn build script
======================
Easy all-in-ones BASH script to build Popcorn-Time for Ubuntu
* [Official Repo](https://git.popcorntime.io)
* [Website](http://popcorntime.io)

Popcorn Time is not developped by me, don't report bugs or ask for features to me.

----

##Use on Ubuntu :
Open a terminal and type : 

    wget https://raw.githubusercontent.com/MrVaykadji/build-popcorn/master/build-popcorn
    bash build-popcorn


###Video Blurp: 

[![Youtube video blurb](http://i.imgur.com/gE16qE4.png)](https://www.youtube.com/watch?v=4cXpNDPUQ_4)

###What does the script do to my machine?
 - it installs Popcorn Time in /opt
 - it brings a light CLI in /usr/bin
 - it creates a launcher in /usr/share/applications

 - it installs nodejs, bower and grunt-cli on your machine
 - it uses a PPA (ppa:chris-lea/node.js) to get latest nodejs version
 - it symlinks libudev.so libraries (only on Ubuntu 12.04 and 12.10)
