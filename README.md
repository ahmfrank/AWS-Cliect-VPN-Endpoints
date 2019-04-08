# AWS-Clioect-VPN-Endpoints
# How to connect AWS VPC though the Tunnelblick
# (1) Download Tunnelblick 3.7.8 as below at https://tunnelblick.net/downloads.html
# (2) Install file DevOps-vpn-v2.ovpn on Tunnelblick in your local machine
# (3) make a connection from Tunnelblick
# (4) Done. Check your VPN connection
# -------------------------------------------------------------
# How To split your local network IPv4 traffic with VPN Tunnel, 
# please add below a modifcation in the DevOps-vpn-v2.ovpn file
# route-nopull
# route 172.31.0.0 255.255.0.0
# Note: 172.31.0.0 255.255.0.0 is your AWS VPC network
