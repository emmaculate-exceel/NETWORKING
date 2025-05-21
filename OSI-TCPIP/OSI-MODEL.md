## Application Layer
* : This layer is the closest to the user, yet it interacts with the applications that request network access. Technically, this layer is for applications, not made of applications. if is the interface layer where applications make requests of the operating system to access the network. Once the request is accepted and delivered, it goes to the presentation layer. Applications that request network access can include apps such as browsers and other local apps using the network, such as MS Word. if you print a document to the network printer in the office, Word will request access through the application layer.

## Presentation layer

* : This layer prepares the data for being transferred. you might say that it being ready to be "presented". Encoding happens here. For instance if you are sending an email in Unicode, it will translate the symbols at this layer. Encryption occurs at this level. in other words, a plaintext or other: unencrypted message is brought through a mathematical algorithm that created encryption. Without knowing the encryption key, the code is nearly unbreakable (though no code is perfect). The sending and receiving network devices share a key at the begining of communication that allows for the algorithm to be reversed and te messaged to be turned back into readable format.

## Session Layer
* : Imagine you have a meeting with somone : you will set the time and place for the meeting maybe other requirements as well (e.g, bring your notebook). This is similar to a session for network communications. The start of communication is agreed upon along, with wait times for responses (acknowledgements) and how the session will be ended(terminated). Once communication is begun, lower layers handles the details .


## Transport Layer

* : Inside a session, the transport layer does the important work of managing the data transfer between hosts. it makes sure that the data flows at the proper rate and performs some error checking. it also breaks down the data into chunks or segments, that are sent out seperately.

## Network Layer

* : If you wish to mail a package to a friend, there are several steps. You put it in an envelope and give it an address . This address is what the network layer uses to transport the data (envelope) to its destination. it does this by using routing. remember that device called router ? that's it primary duty. at every step along the way , the address ischecked and the correct path is chosen to send the data further along toward its destination. in TCP/IP this is where the IP address is used. Data is sent at this level organized into packets.


## Data Link Layer

* : Once the data makes it to it's destination network, it still must find the exact device it is looking for . The data link layer works at a more specific level than the network. it uses hardware address to identify network devices. This is the layer where ethernet specifications dictate low signals are formed as well. it includes local network error checking including collisions. Collisions occur when two network devices send out a signal simultaneously and they collide over physical media. Most networks use collision detection. This means aftera collision is detected both devices are instructed to wait a random amount of time before sending again.


## Physical Layer
* : Network devices are included in this layer such as hubs, switches and routers as well as cabling. The signal itself is included at this layer, where zeros and ones in data are formed into a specific signal and placed on this network.

Data travels back and forth on a network from physical to application and back again. The OSI model is a general model of how network data transmission works, but it is not a required list; different protocols use different concepts from the model.

## Ethernet

* : Ethernet is a set of standards (defined by IEEE 802.3) used for LANs and WANs. The word "Ethernet" is used commonly ot refure to parts of a local wired network, such as Ethernet cabling (Cat 5,5e, 6, 7 and 8), and Ethernet ports, where the cables are connected. The standards of ethernet includes the physical layer, which gives specifications for devices and signals and the data link layer, where it defines where signals is being organized