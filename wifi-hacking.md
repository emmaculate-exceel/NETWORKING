# Wifi sniffing quite educative and explainatory 

### start monitoring which switches the network into monitoring mode
airmon-ng start <interface>

### confirm if the network is now in monitoring mode 
iwconfig 

### scan all surrounding wifi network since our wifi card is now set to monitor mode
airodump-ng <interface>
- note you'll now see all the available wifi networks 

###  to get the information of a specific router or bssid 
airodump-ng -b <macaddress> -c <channel number> <interface>

### to perform sniffing on each of them you'll do 
airodump-ng --bssid <macaddress> --channel <channel value> --write test <interface>

### now to explore and capture the packet from the router 
open wireshark and import the file with the .pcap or .cap 
