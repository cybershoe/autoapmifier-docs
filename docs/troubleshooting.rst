Comon Issues
============

I can't accept the EULA, nothing happens with I click the "I Accept" checkbox
-----------------------------------------------------------------------------
You need to view the EULA before you can accept. Click the
"End User License Agreement" link to open the EULA in a new tab. Once you've
opened the EULA, you can check the "I Accept" box and begin using
the extension.

I've configured a domain to automatically redirect, but it's not triggering the plugin
--------------------------------------------------------------------------------------
Make sure you're using a wildcard if you want to match all subdomains.


+-------------------+---------------------------+
| Pattern           | Matches                   |
+===================+===========================+
| \*.intdomain.local| | intdomain.local         |
|                   | | app1.intdomain.local    |
|                   | | app2.intdomain.local    |
+-------------------+---------------------------+
| intdomain.local   | | intdomain.local **only**|
+-------------------+---------------------------+
