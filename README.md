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

 - it installs nodejs, git, bower and grunt-cli on your machine
 - it uses a PPA (ppa:chris-lea/node.js) to get latest nodejs version
 - it symlinks libudev.so libraries (only on Ubuntu 12.04 and 12.10)


####CLI

    ~$ popcorn-time -h

    Popcorn Time
    ============
    Version : custombuild 'release/rc-0.3.3' 
    Built on 2014.09.06-19h04 from https://git.popcorntime.io/stash/plugins/servlet/archive/projects/PT/repos/popcorn-app?at=refs/heads
    Official website : http://popcorntime.io
    
    Options:
      -h, --help		Display this help.
      -q,--quiet		Launch Popcorn-Time without output.
      --flush		    Flush databases.
      --fix-node		Fix the node-webkit 'blank' error.
      --uninstall		Uninstall Popcorn-Time.
      --issue		    Report an issue.
      --build		    Build latest version from sources.
