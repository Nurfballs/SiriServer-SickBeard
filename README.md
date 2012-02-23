# README #

Installation
=============
1. Download the plugin and place it in your `/plugins` directory.
2. Modify your `plugins.conf` and add the name of the plugin.
3. Restart your SiriServer.

Sabnzbd.py
==========

Description
-----------

Coming Soon

Files
-----
* sabnzbd.py

Version History
---------------

**0.2**

**0.1**

* Initial Release

Functions
---------

This script supports the following functions

* Display current download queue and statistics
* Pause / Resume queue

###Display current download queue and statistics
************************************************

Listen String: `*(sab|sabnzbd|download).*(queue|q|status|stats|statistics)*`

Example: say `download queue` or `sab status` or `download statistics` etc.



### Pause Sabnzbd+ downloads
****************************

Listen String: `(sab|sabnzbd|download|downloads) (pause|stop)`

Example: say `download pause` or `sab stop` etc

### Resume Sabnzbd+ downloads
*****************************

Listen String: `(sab|sabnzbd|download|downloads) (resume|unpause|start)`

Example: say `download resume` or `sab unpause` etc.