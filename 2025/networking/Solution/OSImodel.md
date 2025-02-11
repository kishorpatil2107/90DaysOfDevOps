
This is my solution of week one challenge:
Let’s Understand OSI & TCP/IP Models:

1. OSI Model (7 Layers)
The OSI model is a theoretical framework that standardizes network communication by dividing it into seven layers.
Layer
Name
Function
7
Application
Interfaces with user applications (e.g., HTTP, FTP, SMTP)
6
Presentation
Data translation, encryption, and compression
5
Session
Manages sessions/connections between applications
4
Transport
Ensures reliable or unreliable delivery (TCP/UDP)
3
Network
Handles addressing, routing (IP, ICMP)
2
Data Link
Ensures error-free data transmission (Ethernet, MAC, ARP)
1
Physical
Transmits raw bit stream over physical medium (Cables, Wireless)
Key Points about OSI Model
    • The model is mostly used for learning and troubleshooting.
    • It provides a layered approach for understanding networks.

2. TCP/IP Model (4 Layers)
The TCP/IP model is a practical model used in real-world networking and the internet.
Layer
Corresponding OSI Layers
Function
4
Application (7,6,5)
Handles application protocols (HTTP, FTP, DNS)
3
Transport (4)
Ensures reliable/unreliable data transfer (TCP/UDP)
2
Internet (3)
Handles IP addressing and routing (IP, ICMP)
1
Network Access (2,1)
Manages physical transmission and MAC addressing
Key Points about TCP/IP Model
    • More practical than the OSI model.
    • It directly maps to real networking protocols.
    • Used for communication over the internet.
Comparison of OSI & TCP/IP Models
Feature
OSI Model
TCP/IP Model
Layers
7 Layers
4 Layers
Usage
Theoretical
Practical
Developed by
ISO
DARPA
Protocol Independence
General framework
Internet-based protocols

The TCP/IP model is widely used in real-world networking, while the OSI model is mainly used for learning and troubleshooting.


1️⃣ Application Layer (OSI & TCP/IP) – "User Interaction"
    • Example Protocols: HTTP, HTTPS, FTP, SMTP, POP3, IMAP, DNS
    • Real-World Scenario:
        ◦ When you open a web browser and type www.google.com, HTTP/HTTPS is used to request the webpage.
        ◦ When you send an email via SMTP, it helps transfer messages to a mail server.
        ◦ When you upload/download files using FTP, this layer handles communication.
2️⃣ Presentation Layer (OSI) – "Data Formatting & Encryption"
    • Example Functions: Data encryption (SSL/TLS), compression, character encoding
    • Real-World Scenario:
        ◦ SSL/TLS secures data when accessing a bank website (https://...).
        ◦ JPEG, PNG, MP3, MP4 formats handle image, audio, and video data formatting.
        ◦ Unicode or ASCII ensures text is correctly encoded across different systems.
3️⃣ Session Layer (OSI) – "Maintaining Connections"
    • Example Functions: Session establishment, authentication, API calls
    • Real-World Scenario:
        ◦ When logging into a website, OAuth authentication maintains your session.
        ◦ Video conferencing apps like Zoom or Skype use this layer to manage session states.
        ◦ Online banking keeps your session active while you're logged in.
4️⃣ Transport Layer (OSI & TCP/IP) – "Reliable Data Delivery"
    • Example Protocols: TCP, UDP
    • Real-World Scenario:
        ◦ TCP (Transmission Control Protocol) ensures reliable delivery of web pages (e.g., when loading a website, lost packets are resent).
        ◦ UDP (User Datagram Protocol) is used in live streaming (YouTube, Netflix), VoIP calls, and gaming where speed is prioritized over accuracy.
5️⃣ Network Layer (OSI & TCP/IP) – "Routing & Addressing"
    • Example Protocols: IP, ICMP, ARP
    • Real-World Scenario:
        ◦ When you enter a website URL, DNS resolves it to an IP address, and IP routing finds the best path.
        ◦ Ping commands (ICMP) help troubleshoot network connectivity.
        ◦ Routers use IP addresses to forward packets to the correct destination.
6️⃣ Data Link Layer (OSI) / Network Access Layer (TCP/IP) – "MAC Addresses & Switching"
    • Example Protocols: Ethernet, Wi-Fi (802.11), MAC, PPP
    • Real-World Scenario:
        ◦ Wi-Fi routers use 802.11 protocols to connect devices wirelessly.
        ◦ When two computers are connected via Ethernet, MAC addresses help identify specific devices.
        ◦ Switches operate at this layer to forward frames based on MAC addresses.
7️⃣ Physical Layer (OSI) / Network Access Layer (TCP/IP) – "Hardware & Transmission"
    • Example Components: Cables, Fiber optics, Radio signals, Network Interface Cards (NIC)
    • Real-World Scenario:
        ◦ When you plug an Ethernet cable into your laptop, it operates at the physical layer.
        ◦ Fiber optic cables enable high-speed internet connections.
        ◦ Wi-Fi signals, Bluetooth, and 5G transmit data wirelessly over radio waves.