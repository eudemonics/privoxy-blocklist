# privoxy-blocklist
=================

Bash script converting AdBlock Plus rules and Adguard filters into privoxy format.

Forked from original script written by **Andrwe Lord Weber**. Updated by **vvn** to include Adguard filters and some other functions.

###TO USE:

Copy privoxy-blocklist.sh and blocklist.conf into your privoxy config directory.

Default location for config on Linux is **/etc/privoxy** and on OSX is **/usr/local/etc/privoxy**.

Edit blocklist.conf and the top few lines of privoxy-blocklist.sh to your own setup. Make sure that all paths exist and are accessible, and user/group settings are correct.

Execute commands in terminal from within privoxy config directory:

> chmod +x privoxy-blocklist.sh

> sudo ./privoxy-blocklist.sh

**You can keep the adblock filters updated automatically by creating a crontab to run the script as often as you prefer.**
