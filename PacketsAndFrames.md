<h1>Packets and Frames</h1>

<h3>Packet:</h3> 
- A piece of data from the network layer of the OSI model, containing information such as an IP header and payload.
- Has headers such as Time to Live, Checksum, source address, Destination address

<h3>Frame:</h3> 
- Used at Data Link layer of the OSI model to encapsulate packets and add additional information such as a MAC address.

<h3>TCP/IP</h3>
- Consists of the Application, Transport, internet, Network Interface layers.
- Connection based, connection must establish between client and server before data can be sent
- capable of synchronizing two devices to prevent flooding with data in the wrong order
- Slower than UDP
- TCP packet format [Source Port | Destination port | Source IP | Destination IP | Sequence number | Acknowledgement number | Checksum | Data | Flag] \


<h3>UDP/IP</h3>
- Stands for User Datagram Protocol
- is a stateless protocol that doesn't require a constant connection, no three-way handshake or synchronization.
- Used in video streaming, voice chat
- Much faster than TCP, but does not care if data is received or not
- UDP packet format [ TTL | Source addr. | Dest. addr | Source Port | Destination Port | Data]
- Request, Response

<h3>Ports</h3>
- 21: FTP
- 22: SSH
- 80: HTTP
- 443: HTTPS
- 445: SMB (like ftp but works with printers' esc.)
- 3389: RDP
