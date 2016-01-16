omxcontrol
==========

Nodejs module to control omxplayer. Specifically written for the raspberry pi

Requirements
------------

* omxplayer (installed by default on the raspberry pi raspian image)
* nodejs (`apt-get install nodejs`)

Install
-------

    npm install simpleomxcontrol

Usage
-----

Basic usage
    
    omx = require('omxcontrol');

    omx.start(filename);

    omx.pause();

    omx.forward();

    omx.backward();

    omx.subs();

    omx.quit();

