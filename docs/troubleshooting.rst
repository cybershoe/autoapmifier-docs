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

My settings don't sync betweeen Chrome browsers
-----------------------------------------------

This is by design. The extension does not currently support network location
awareness, so a user with a both a home and office computer, for example, might
not want the same settings on both computers. If the extension is enhanced to
include location awareness, settings sync will be reconsidered at that time.

I have a different question/idea/suggestion
-------------------------------------------

Feedback is welcome, either through the Chrome extension feedback system, or by
e-mail at autoapmifier@f5.com. Please note that
this is a side-project from the F5 field engineering team, and not an official 
F5 product; as such, updates may be infrequent or not happen at all.