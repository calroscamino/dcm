# vpn script for openconnect

```
#----- How to install
#
#   DL and save this to your $HOME
#
#   1) Set static values of your own
#   OTPSEQ:   authentication pattern
#   USERNAME: employee number 
#   SERVER:   VPN connector's FQDN
#   DVI_SV:   VDI server's FQDN
#
#   2) Run once to change permissions and privileges
#   % chmod +x ./vpnc-script
#   % ./vpnc-script setup 
#
#----- Usage Guide
#
# % ./vpnc-script [setup | start | stop ]
#
#    setup : once need to run before [start]
#    start : start to initiate the vpn
#    stop  : stop the concurrent vpn process 
#
```
