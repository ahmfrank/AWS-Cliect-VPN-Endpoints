# AWS-Clioect-VPN-Endpoints
# How to configure ovpn file for Tunnelblick
# (1) Download Tunnelblick 3.7.8 as below at https://tunnelblick.net/downloads.html
# (2) Install file DevOps-vpn-v2.ovpn on Tunnelblick in your local machine
# (3) To split your local network IPv4 traffic and VPN Tunnel, please add below configure on the ovpn file
# route-nopull
# route 172.31.0.0 255.255.0.0
# Note: 172.31.0.0 255.255.0.0 is your AWS VPC network
