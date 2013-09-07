AmnesiaScriptToolbox
====================

A bunch of general purpose scripts and structures to help with Amnesia map creation.
This collection of scripts assumes you have access to a pre-processor to #include the relevant scripts into your map script.

Limitations in scripts
====================
Cannot use the following due to limitations in Amnesia's version of Angelscript:

Classes: Static methods/members, private non-void return type functions, const members inside class
Callbacks: Callbacks to Amnesia scripts must be in global scope
Function pointers: No way to save / restore state on save/load occurance
