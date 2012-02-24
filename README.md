sickbeard.py
============

Description
-----------
This plugin will allow you to use Siri in conjunction with SiriServer, to perform actions with SickBeard via voice commands.


Pre-requisites
--------------
1. A working installation of SiriServer.
2. A working installation of SickBeard.

The installation and configuraiton of the pre-requisites are outside the scope of this readme. 

If you do not have these applications configured, please seek further instruction from the installation guides for each application.


Installation
------------
1. Download `sickbeard.py` and place it in your `/plugins` directory.
3. Edit `sickbeard.py` and add the IP Address, Port and API Key of your SickBeard installation.
2. Edit your `plugins.conf` and add `sickbeard` to the list of plugins to load.
3. Restart your SiriServer.

Functions
---------

This script supports the following functions

* Add shows to SickBeard
* Display upcoming shows this week

**Add a show to SickBeard**

Listen String: `(download) (tv) (show|shows)* ([\w ]+)`

Example: say `download tv show The Big Bang Theory` etc.


**Display upcoming shows this week**

Listen String: `.*new.*(tv|episode|show).*`

Example: say `what new shows are out this week` etc


**Restart SickBeard**

Listen String: `sickbeard.*(restart|reboot|reset).*`

Example: say `sickbeard restart` or `sickbeard reboot` etc.



Version History
---------------

**0.2**

**0.1**

* Initial Release
