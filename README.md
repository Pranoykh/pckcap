#  Capture and Analyze Network Traffic Using Wireshark.

***Protocols Identified***

1. ARP
2. DNS
3. ICMP
4. TCP
5. TLSv1.2

***Definitions***

1. **ARP(Address Resolution Protocol)** :

   It is a communication protocol used to find the ***Media Access Control (MAC) Address*** associated with a given ***Internet Protocol (IP) Address***. It is a fundemental protocol for the delivery of data packets within a local area network, such as your home network.
   
2. **DNS(Domain Name System)** :

   It is a protocol that translate human-readable domain name (like ```www.facebook.com```) into computer-friendly IP Address (like ```157.240.192.35```). Think of it as the internet's phonebook: You look up a person's name to find their phone number. DNS does the same thing, allowing you to easy-to-remember named instead of a long string of numbers.

3. **ICMP(Internet Control Message Protocol)** :

   It is a core network layer protocol used by devices to exchange vital information and report errors. Unlike other protocols like TCP or UDP, ICMP isn't used to transfer application data (like a webpage or an emaiil). instead, it's primary functions is to provide a "status report" for the network, helping devices communicate issues and perform diagnosics.

3. **TCP(Transmission Control Protocol)** :

   It is a foundational protocol of internet that provides a reliable, ordered and error-checked delivery of data between applications. It is part of the Internet Protocol (IP) suite, and the two are often referred to together as TCP/IP.

   Unlike it's counterpart, UDP(User Datagram Protocol), TCP is connection-oriented. This means that before any data is sent, the two devices must establish a stable connection. TCP's primary goal is to ensure that every single data packet sent arrives at it's destination without errors and in the correct order.

4. **TLSv1.2(Transport Layer Security Version 1.2)** :

   It is a widely used cryptographic protocol designed to provide secure communication over a computer network. It is the successor to SSL(Secure Sockets Layer) and an earlier version of TLS(TLSc1.0 and TLSv1.1)
