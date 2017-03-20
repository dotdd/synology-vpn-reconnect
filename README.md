# Synology VPN Reconnect Script
I noticed my VPN sometimes stopped responding (403 errors outbound, etc). So I made a 'simple' bash script. This script is tested on DSM 6.0.2-8451 Update 4 in combination with the OpenVPN protocol, but should also work on DSM 6.1+.

This script works fine with sudo-enabled users (admin by default) from the command line, but will you will need to set the user to 'root' when running as scheduled task (see step 5 of the installation) since sudo requires you to re-enter your password on every run!

## Instructions and changelog
See detailed instructions in the [wiki](https://github.com/DcR-NL/synology-vpn-reconnect/wiki)