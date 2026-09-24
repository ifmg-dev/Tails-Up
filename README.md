Tails-Up
Instructions, Go to tailcale and create a script for a linux cli connection and enable advertise exit nodes,
then go to your VPS server and paste the script to install tailscale and connect it to your system. 
Then go to your vpn provider of choice and download a wireguard config and move it to your servers "/etc/wireguard" folder,
If the directory dosent exits make it then move it, Then run one of the scripts to have the VPS route your traffic acting as your own private VPN with DNS over TLS for encryption
with the choice of single or double hop(s) to provide IP And DNS query obfuscation.


Useful Urls

Tailscale Create Linux Server Connection
https://console.tailscale.com/admin/machines/new-linux

Proton VPN Wireguard Download Page
https://account.protonvpn.com/downloads
