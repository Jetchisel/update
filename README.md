# Update - A bash script that manage an update for packages in openSUSE.

Copyright 2014-2015, Jetchisel

# The following are done by the update script (which is my personal choice.)

* Disable multiversion kernel in /etc/zypp/zypp.conf
* Disable delta rpm in /etc/zypp/zypp.conf.
* Disable autorefresh of repositories.
* Enable package cache of all enabled repositories.
* Update system packages.

# Installation

* Put the script somewhere in your PATH
* Make it executable
* call the script: update
