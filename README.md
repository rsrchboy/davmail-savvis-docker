# Davmail in a box!

This image is an extension of *gimoh/davmail:latest*, to do a couple additional
things:

* Run as not-root;
* Log potentially useful messages to console, where *docker logs* can get at them; and
* Default to the Savvis/CenturyLinkLabs Exchange server.

This image is intended to be used as a local proxy **only**.  No security
between one's local mail/etc clients and the davmail instance running in the
container is configured.

## Auto-rebuild on update

The docker hub is configured to rebuild this image whenever upstream (that is,
*gimoh/davmail:latest*) is rebuilt.

# Author and License

Copyright (c) 2014 by Chris Weyl \<christopher.weyl@savvis.com\>.  (That is,
effectively by CenturyLinkLabs.)

[![][51]][50] | This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][50].

[50]: http://creativecommons.org/licenses/by-sa/4.0/ "Creative Commons License"
[51]: http://i.creativecommons.org/l/by-sa/4.0/88x31.png "Creative Commons License CC-BY-SA"
