AmnesiaScriptToolbox
====================

A bunch of general purpose scripts and structures to help with Amnesia map creation.
This collection of scripts assumes you have access to a pre-processor to #include the relevant scripts into your map script.

Limitations in scripts
====================
Cannot use the following due to limitations in Amnesia's version of Angelscript:

Classes: Static methods/members, private non-void return type functions, const members inside class

Callbacks: Callbacks to Amnesia scripts must be in global scope

Function pointers: No way to save / restore state on save/load occurance.

Beta Functions
====================
This toolbox assumes you are running the latest version of amnesia. Only this version is supported!
Currently, the latest version is a beta and can be obtained at the following link:
http://www.frictionalgames.com/forum/thread-23378.html
