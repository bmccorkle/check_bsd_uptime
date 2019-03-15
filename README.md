# check_bsd_uptime
Monitoring Plugin to check FreeBSD Uptime


usage: $0 [ -h ] [-c OPTION] [-w OPTION] [-f OPTION] [ -V ]
This script checks uptime and optionally verifies if the uptime
is below MINIMUM or above MAXIMUM uptime threshholds
OPTIONS:
   -h   Help
   -c   CRIT min uptime (minutes)
   -w   WARN min uptime (minutes)
   -f	Flip Thresholds (MAX minutes instead of minimum)
   -V   Version
