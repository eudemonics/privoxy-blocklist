privoxy-blocklist
=================

Bash script converting AdBlock Plus rules and Adguard filters into privoxy format.

Forked from original script written by Andrwe Lord Weber. Updated by vvn to include Adguard filters and some other functions.

**TO USE:

Copy privoxy-blocklist.sh and blocklist.conf into your privoxy directory. Default location for script is at /usr/local/etc/privoxy.

Edit blocklist.conf to your own setup. Make sure all paths and user/group settings are correct.

Run commands within privoxy folder:

chmod +x privoxy-blocklist.sh

sudo ./privoxy-blocklist.sh
