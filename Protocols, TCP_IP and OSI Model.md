### Protocols, TCP/IP and OSI Model

## What are Protocols?
Protocols are the set of rules and regulations that device follow to transfer and recieve data over a wired or wireless medium.

## TCP/IP Model
![094f9328dd94980ca6cf2418d57c90e2.png](https://github.com/Mrpai2318/Ethical-Hacking-Notes/blob/main/_resources/8b7d70fdbb19489eba0bf6fa5a805e31.png)

It has 4 layers to it as follows:-
4. Application Layer:-  It encodes and encrypts the data so that the computer can understand it and then it creates sessions. Sessions are used to establish comunication between 2 devices. It involves signalling to setup and manage communication between two devices. Eg: Brower
Protocols are FTP, HTTP/HTTPS, Telnet
3. Transport Layer:- It adds port number. Protocols are TCP & UDP
2. Network Layer:- It adds senders and receivers address on the data packet. It handles IP addressing, routing and virtual pathing. It adds MAC address of the client and the server to the data packet. Protocols are DHCP, ARP, ICMP.
1.Physical Layer:- This is where the binary data is coneverted into electrical signals for data transfer. It also checks itself for errors. Eg: Wifi adapter, Protocols are Ethernet, 802.11, DSL.

## TCP/IP Stack
![f631014aad9f32de6ae1abe7afb659f2.png](https://github.com/Mrpai2318/Ethical-Hacking-Notes/blob/main/_resources/97906de8eecd4193996e3500b07d2698.png)

## TCP/UDP & IP Protocols
TCP(Transmission Control Protocol)
UDP (User Datagram Protocol)
Differences betwen TCP & UDP are:-
![2d5356134ff8b588aaeadfd5c05de9fc.png](https://github.com/Mrpai2318/Ethical-Hacking-Notes/blob/main/_resources/97906de8eecd4193996e3500b07d2698.png)

IP(Internet Protocol)
DHCP(Dynamic Host Configuration Protocol)

![f3c8c8ef7eddeba4351e25682850eb46.png](https://github.com/Mrpai2318/Ethical-Hacking-Notes/blob/main/_resources/c8fa1a57fd674a9fb11ea75f7b73ccd7.png)

## OSI Model 
Just like in the TCP/IP model, the data in the OSI model also passes from layer 7 to layer 1 at the sender’s end and from layer 1 to layer 7 at the receiver’s end.

* Application Layer- This layer provides an interactive interface for the user to enter and view data. One can give inputs in the form of text, audio, images, files, etc. The browser makes up the application layer.

* Presentation Layer- After the application layer, the data passes to the presentation layer. This is where the data is converted into computer friendly format, i.e in binary code. So, the presentation layer encodes the input, compresses it, and encrypts it if required. Then the data is sent to the next layer.

* Session Layer- This layer initiates a connection and creates a session, so that some context can be provided to the communication between the two devices.

* Transport Layer- This layer establishes an application level connectivity. For this, it attaches the source and destination port numbers. It also performs the task of error control, which means that it makes a checklist, so that it can be cross checked at the receiving end to ensure that all the data is transferred properly and not destroyed on the way. These checklists are known as checksums. 

* Network Layer- At the network layer, the source and destination IP addresses are attached, for the purpose of identification of devices, and to decide the virtual path that needs to be taken by the data packet. So, we can say that this layer does network level routing and pathing of packets.

* Data Link Layer- This layer attaches the source and destination MAC addresses, which are used to identify the hardware of the device. It also calculates checksums for error checking of the metadata that has been attached at all the previous layers, and also to manage the flow of data.

* Physical Layer- This is where the data is converted to hardware friendly signals, like radio signals, light signals, or electric signals, depending on the hardware that is being used for data transfer.

![osimodel](https://github.com/Mrpai2318/Ethical-Hacking-Notes/blob/main/_resources/osimodel.png)
