# TCP/IP MODEL

---

### TCP/IP stands for Transmission Control Proctocol/Internet Protocol. The transmissions control protocol works at the transport layer , while the internet protocol works at the network layer of the OSI model. However, TCP has it own four layer model of operating.


---

* : TCP/IP is the protocol of the internet . That means that to access the internet, it must be installed on a device. Since itis also usable for LAN communication, most computers use TCP/IP as their primary and only network protocol. it consist of other sub-protocols that exist within it to facilitate communications. to use TCP/IP a network device must be configured with 3 settings . these settings are 32-bits binary numbers (or 128-bit with the new IPv6 version) .

### IP

* : This is the unique address of the network device; there cannot be a duplicate on the same network. it is divided into two parts: a network ID (which identifies what network segment the device is on) and the host ID(which is the individual device number). A good analogy is that  the network ID is like a street and the host ID is like a house number.

### Subnet mask

* : This is a series of ones and zeros that identifies which part of the address is the network ID and which is the host ID. IP addresses have the option of being split in different places depending on the need of the network.

### Defualt Gateway

* : The gateway is the router or device that allows the computer to access other devices outside of its local network if a computer is taling to a device on its own network it does not need a gateway, but once it wants to talk to a host outside its network it must use a gateway.


### Packet Delivery
* : Let return to our analogy of sending a mail in an envelope but with more details this time. Let's say you're sending a picture of your cat Over the Skype to your grandmother in Canada. The data is formatted and presented for transport over the internet. Then a session is established. The picture of your cat is ten broken down into individual packets. Each packet is like a seperate box of data. The box will have 2 addresses on it; the sender's and the recipient's.


### Fault Tolerance

* : TCP/IP is also fault-tolerant. During a session. it checks to make sure all packets are recieved and continually verifies the path. if, for some reasons a router along the path to the destination stops functioning, TCP/IP will automatically look for ( and,most often, find) a different path to continue to deliver the data. This is why the internet never completely goes "down" as a whole; part of it may stop workiing, but the rest of this vast network continues functioning without those parts. 