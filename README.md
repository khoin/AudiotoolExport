Audiotool Export
=====================

![As of April 2016](http://i.imgur.com/DwleXMx.png)
Audiotool Export as of April 2016.

# Libraries & Stylesheets

Here are the libraries that helped in the development of this small app:

* [jsmidgen](https://github.com/dingram/jsmidgen) Handles the MIDI format and structure
* [FileSaver.js](https://github.com/eligrey/FileSaver.js/) Handles file-saving.
* [Bootstrap CSS Grid](http://getbootstrap.com) CSS Grid-system for responsiveness.  

# Overview

**Authenticate > Choose Project > Choose Regions > Choose Options > Save!** 

* **MIDI**: You have to choose note regions before exporting to MIDI. Maximum of 16 can be chosen as MIDI limits to 16 tracks. 
* **LMMS**: You can save your project entirely to LMMS without choosing note regions. Currently, only note tracks are exported and Pulverisateur patches will be translated to OSCx3 of LMMS as close as possible. The output file type is `.mmp` not `.mmpz` so it is uncompressed. However, you can just open it in LMMS and save it under `.mmpz`.

# Issues

* If the regions you exported isn't displayed like how it is on Audiotool, please open an issue.