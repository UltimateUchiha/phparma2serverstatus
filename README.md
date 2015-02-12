PHP Arma2 Server Status
==============================

https://github.com/firefly2442/phparma2serverstatus

phparma2serverstatus queries Arma2, Arma3, and DayZ servers through PHP and displays information about the server
such as the map that is running, connected players, and other information.

Setup:

Change directory (cd) into the phparma2serverstatus folder.
Run: `git submodule update --init`

This will grab the GameQ dependency submodule.

Edit the `config.inc.php` file and specify the IP addresses and ports for the servers you
want to query.  That's it.  Then just navigate to the page to see the results.


3rd Party Libraries:

This software uses a forked custom version of GameQ (version 2):

http://gameq.sourceforge.net/

At this time, there appears to be no activity or further development on the Sourceforge
version of GameQ.  Another Git repository with more recent work is here:

https://github.com/Austinb/GameQ

JQuery (MIT license):

http://jquery.org/

License:

This software is licensed under the GPL version 3.0 (see license.txt).

GameQ is licensed under the GPL.

Arma2, Arma3, and associated images are copyrighted/trademarks of their respective owners.

GeoIP Lookup provided by:

http://www.hostip.info

Here are some of the past questions and responses regarding querying Arma2
servers using the Gamespy protocol:

http://forums.bistudio.com/showthread.php?126642-PHP-server-query-available-somewhere-Or-some-related-info

http://forums.bistudio.com/showthread.php?133442-Getting-server-data-for-webpage

http://forums.bistudio.com/showthread.php?78332-Server-Query-Documentation

Thanks To:

AlphaSquad for help with testing and development
http://www.alphasquad.net
