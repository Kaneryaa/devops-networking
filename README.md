# Computer networking basics 
Computer networking involves the interconnection of various devices and systems to enable them to communicate and share resources. Here are some basic components and concepts in computer networking

## Components
 **Devices**:

- Computers: These can be desktops, laptops, servers, or any device capable of running networking software.
- Switches and Routers: These are critical devices for directing network traffic. Switches connect devices within a local area network (LAN), while routers connect different networks and manage traffic between them.

**Network Interface Cards (NICs)**:

- NICs are hardware components that allow devices to connect to a network. They provide a physical connection to the network medium (like Ethernet cables or Wi-Fi).

**Cabling and Connectors**:

- Ethernet Cables: These are commonly used for wired network connections. They come in different categories (e.g., Cat5e, Cat6, Cat6a) which determine their speed and bandwidth capabilities.
- Fiber Optic Cables: These use light signals to transmit data and are capable of high-speed, long-distance communication.
- Wireless: Wi-Fi is a common wireless networking technology that allows devices to connect without physical cables.

**Network Protocols:**

- Protocols are rules that govern how data is transmitted, received, and formatted in a network. Examples include TCP/IP (Transmission Control Protocol/Internet Protocol), HTTP (Hypertext Transfer Protocol), and FTP (File Transfer Protocol).
  
**IP Addresses:**

- IP addresses uniquely identify devices on a network. IPv4 and IPv6 are the two main versions of the Internet Protocol in use today.
  
**Subnetting:**

- Subnetting involves dividing a network into sub-networks to improve performance, security, and manageability.
  
**Network Topologies:**

- Topology refers to the physical or logical layout of a network. Common topologies include bus, star, ring, and mesh.

**LAN and WAN:**

- LAN (Local Area Network): A network limited to a small geographic area, like a single building or a campus.
- WAN (Wide Area Network): Spans a large geographic area, often connecting multiple LANs across cities or countries.

**Firewalls and Security Devices:**

- Firewalls control the incoming and outgoing network traffic based on an applied rule set. They are a critical component of network security.

**DNS (Domain Name System):**

- DNS translates human-readable domain names (like www.example.com) into IP addresses that machines can understand.

**DHCP (Dynamic Host Configuration Protocol)**:

- DHCP automatically assigns IP addresses to devices on a network, making it easier to manage large networks.

**Gateway**:

- The gateway is a device that connects a local network to the internet. It serves as an entry and exit point for data traffic.
- These are some fundamental components and concepts in computer networking. Understanding these basics is crucial for setting up and managing networks effectively.

  
## OSI Models 

**Physical Layer (Layer 1):**

- Function: This layer deals with the physical connection between devices. It defines the hardware, cables, and electrical signals used for transmission.
- Example: When you plug an Ethernet cable into a computer and a router, the physical layer is responsible for ensuring that electrical signals representing data can travel between them.

**Data Link Layer (Layer 2):**

- Function: This layer focuses on reliable point-to-point communication between directly connected devices. It handles issues like addressing, error detection, and flow control.
- Example: When you send a message over Wi-Fi, the data link layer ensures that the data frames are properly addressed to the intended recipient within your local network.

**Network Layer (Layer 3):**

- Function: The network layer enables communication between different networks. It's responsible for routing, logical addressing, and packet forwarding.
- Example: When you send an email to someone in a different city, the network layer determines the best path for your email to reach its destination across various routers and networks.

**Transport Layer (Layer 4):**

- Function: This layer ensures end-to-end communication and handles data flow control. It also addresses issues like reliability and error correction.
- Example: When you're streaming a video, the transport layer (TCP, for example) ensures that the video frames arrive in the correct order and retransmits any lost data packets.

**Session Layer (Layer 5):**

- Function: The session layer establishes, manages, and terminates connections or sessions between applications. It handles tasks like authentication and synchronization.
- Example: When you log into a website, the session layer is involved in setting up and maintaining the connection between your browser and the server.

**Presentation Layer (Layer 6):**

- Function: This layer handles data translation and encryption, ensuring that information sent by one system can be understood by another. It also manages data compression.
- Example: When you download a file, this layer could be responsible for decompressing it and making sure it's in a format your computer can understand.

**Application Layer (Layer 7):**

- Function: The application layer is closest to the end-user and provides network services directly to user applications. It includes protocols for tasks like email, file transfer, and web browsing.
- Example: Browsers like Chrome or Firefox use application layer protocols like HTTP or HTTPS to retrieve and display web pages.

![image](https://github.com/Kaneryaa/devops-networking/assets/89991677/89e0f3e6-a47f-4a27-b26e-2aa9b777aab4)



## Classification 
Networks can be classified by geography based on their physical scope and coverage area. The three major classifications are:

**LAN (Local Area Network):**

- Scope: A LAN covers a relatively small physical area, typically within a single building or a campus.
- Example: In an office building, all computers, printers, and servers connected to a common switch or hub form a LAN. This allows for easy sharing of resources like files and printers.

**MAN (Metropolitan Area Network):**

- Scope: A MAN covers a larger geographic area, such as a city or a campus with multiple buildings.
-Example: A university campus with multiple buildings might have a MAN connecting all the buildings, allowing for centralized services like a shared library database or centralized email servers.

**WAN (Wide Area Network):**

- Scope: A WAN spans a large geographic area, potentially a country or even multiple countries. It can be a collection of LANs and MANs interconnected over a wide area.
- Example: The internet itself is the largest WAN. Companies with offices in different cities or countries often use WANs to connect their various branches.

## IP Adress 
IP, or Internet Protocol, is a set of rules that govern how data packets should be sent, received, and routed across a network. It is an essential component of internet communication. IP allows devices to communicate with each other over the internet by assigning unique addresses to each device.

IPv4 (Internet Protocol version 4) and IPv6 (Internet Protocol version 6) are two different versions of the IP protocol.

**IPv4**:

- **Address Format**: IPv4 addresses are 32-bit binary numbers, typically represented in a human-readable form as a series of four decimal numbers separated by periods (e.g., 192.168.0.1).
  
- **Address Space**: It provides approximately 4.3 billion unique addresses, which were thought to be more than enough when IPv4 was developed.

- **Address Classes**: IPv4 addresses are categorized into five classes: A, B, C, D, and E. Classes A, B, and C are used for unicast addressing (one-to-one communication), class D is used for multicast addressing (one-to-many communication), and class E is reserved for special purposes.

  - **1st Octet**: The first octet (8 bits) of an IPv4 address is used to determine the address class and the network portion of the address.
  
  - **2nd and 3rd Octets**: These octets are used to identify the network within the class.

  - **4th Octet**: This octet is used to identify the specific device on the network.

**IPv6**:

- **Address Format**: IPv6 addresses are 128-bit binary numbers, represented as eight groups of four hexadecimal digits, separated by colons (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).

- **Address Space**: IPv6 provides an enormous number of unique addresses, approximately 340 undecillion (3.4x10^38), ensuring that we don't run out of addresses anytime in the foreseeable future.

**Differences**:

1. **Address Length**: The most noticeable difference is the address length. IPv4 uses 32 bits while IPv6 uses 128 bits.

2. **Address Representation**: IPv4 addresses are in decimal format separated by periods, while IPv6 addresses are in hexadecimal format separated by colons.

3. **Address Space**: IPv6 has a significantly larger address space compared to IPv4, which was the main motivation for its development.

4. **Address Configuration**: IPv4 addresses can be manually assigned (static) or obtained from a DHCP server. IPv6 addresses can be automatically generated based on the device's MAC address or obtained through DHCPv6.

5. **Address Types**: IPv4 has unicast, broadcast, and multicast addresses. IPv6 does not have a broadcast mechanism but relies heavily on multicast.

6. **Subnetting**: IPv6 was designed with more efficient and hierarchical addressing, making subnetting and routing simpler compared to IPv4.

7. **NAT (Network Address Translation)**: NAT is commonly used in IPv4 to allow multiple devices in a private network to share a single public IP address. In IPv6, the need for NAT is reduced due to the vast address space.

8. **Backward Compatibility**: IPv6 is designed to be backward compatible with IPv4, but not the other way around. This means that an IPv6 network can communicate with IPv4 networks through various transition mechanisms.


![image](https://github.com/Kaneryaa/devops-networking/assets/89991677/496ae2b5-21de-464e-8d91-559094f6fb9e)


## Protocol 

**Protocol:**

A protocol in the context of computer networking refers to a set of rules that govern how data is transmitted, received, and processed across a network. These rules ensure that devices can communicate effectively with one another. Protocols define things like the format of data packets, how devices establish and terminate connections, error handling, and more.

In the OSI (Open Systems Interconnection) model, which is a conceptual framework used to understand how different networking protocols work together, protocols are organized into layers. Each layer has a specific function and communicates with the layers above and below it. The OSI model has seven layers:

**Application Layer:**

This is the top layer and deals with the protocols and data formats that applications use for communication over a network (e.g., HTTP for web browsing, SMTP for email).

**Presentation Layer:** 

This layer handles data encoding, encryption, and compression to ensure that data is presented in a format that the application layer can understand.

**Session Layer:**

It establishes, maintains, and terminates connections between applications. It also manages sessions (long-running connections) and ensures data synchronization.

**Transport Layer:**

This layer is responsible for end-to-end communication. It takes care of reliable data delivery, error checking, and flow control. Two of the most common transport layer protocols are TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).

**Network Layer:**

This layer is responsible for routing packets across networks. It determines the best path for data to travel from the source to the destination, using devices like routers. IP (Internet Protocol) operates at this layer.

**Data Link Layer:**

This layer deals with the physical connection between devices. It handles tasks like addressing (using MAC addresses), framing, and error detection.

**Physical Layer:**

This is the lowest layer and deals with the actual hardware, including cables, switches, and network interface cards. It's responsible for transmitting raw binary data over a physical medium.

**Port Numbers:**

In networking, a port is a logical endpoint for communication. It's like a door on a computer or server that allows specific types of data to come in or go out. Each port is associated with a number, known as the port number, ranging from 0 to 65535.

- Well-Known Ports (0-1023): These are reserved for specific protocols and services. For example, HTTP typically uses port 80, HTTPS uses port 443, and FTP uses port 21.

- Registered Ports (1024-49151): These are used by software applications and services but are not as universally recognized as well-known ports.

- Dynamic or Private Ports (49152-65535): These are typically used for temporary or dynamically assigned services.

- Ports work in conjunction with protocols. For example, when you browse a website using a web browser (which uses the HTTP protocol), your browser sends a request to the server's IP address on port 80 (for HTTP) or port 443 (for HTTPS). The server's software is configured to listen for incoming requests on these ports and responds accordingly.


## Network Command 



```

1. `sudo -i`
   - *Output*: 
     ```
     [sudo] password for user:
     root@your_computer:~#
     ```

2. `ifconfig`
   - *Output*: 
     ```
     eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
             inet 192.168.1.100  netmask 255.255.255.0  broadcast 192.168.1.255
             inet6 fe80::a00:27ff:fe6b:3f6c  prefixlen 64  scopeid 0x20<link>
             ether 08:00:27:6b:3f:6c  txqueuelen 1000  (Ethernet)
             RX packets 29256  bytes 19873901 (19.8 MB)
             RX errors 0  dropped 0  overruns 0  frame 0
             TX packets 13915  bytes 1837405 (1.8 MB)
             TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

     lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
             inet 127.0.0.1  netmask 255.0.0.0
             inet6 ::1  prefixlen 128  scopeid 0x10<host>
             loop  txqueuelen 1000  (Local Loopback)
             RX packets 157  bytes 12864 (12.8 KB)
             RX errors 0  dropped 0  overruns 0  frame 0
             TX packets 157  bytes 12864 (12.8 KB)
             TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
     ```

3. `ip addr show`
   - *Output*:
     ```
     1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
         link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
         inet 127.0.0.1/8 scope host lo
            valid_lft forever preferred_lft forever
         inet6 ::1/128 scope host
            valid_lft forever preferred_lft forever
     2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP group default qlen 1000
         link/ether 08:00:27:6b:3f:6c brd ff:ff:ff:ff:ff:ff
         inet 192.168.1.100/24 brd 192.168.1.255 scope global dynamic eth0
            valid_lft 78016sec preferred_lft 78016sec
         inet6 fe80::a00:27ff:fe6b:3f6c/64 scope link
            valid_lft forever preferred_lft forever
     ```

4. `ping servoxi.com`
   - *Output*: 
     ```
     PING servoxi.com (104.21.234.15) 56(84) bytes of data.
     64 bytes from 104.21.234.15 (104.21.234.15): icmp_seq=1 ttl=60 time=11.5 ms
     64 bytes from 104.21.234.15 (104.21.234.15): icmp_seq=2 ttl=60 time=11.6 ms
     ...
     ```

5. `tracert www.google.com`
   - *Output*: (On Linux, it's `traceroute`)
     ```
     traceroute to www.google.com (172.217.7.196), 30 hops max, 60 byte packets
      1  gateway (192.168.1.1)  1.237 ms  1.493 ms  1.692 ms
      2  * * *
      3  172.24.32.1 (172.24.32.1)  9.065 ms  9.303 ms  9.615 ms
      ...
     ```

6. `netstat -antp`
   - *Output*: 
     ```
     Proto Recv-Q Send-Q Local Address           Foreign Address         State       PID/Program name
     tcp        0      0 0.0.0.0:22              0.0.0.0:*               LISTEN      940/sshd
     tcp        0      0 127.0.0.1:631           0.0.0.0:*               LISTEN      1112/cupsd
     ...
     ```

7. `nmap localhost`
   - *Output*: 
     ```
     Starting Nmap 7.80 ( https://nmap.org ) at 2021-09-24 11:25 UTC
     Nmap scan report for localhost (127.0.0.1)
     Host is up (0.000065s latency).
     Not shown: 996 closed ports
     PORT     STATE SERVICE
     22/tcp   open  ssh
     80/tcp   open  http
     631/tcp  open  ipp
     3306/tcp open  mysql
     ...
     ```

8. `dig www.google.com`
   - *Output*: 
     ```
     ; <<>> DiG 9.16.1-Ubuntu <<>> www.google.com
     ;; global options: +cmd
     ;; Got answer:
     ;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 1271
     ;; flags: qr rd ra; QUERY: 1, ANSWER: 6, AUTHORITY: 0, ADDITIONAL: 1
     ...
     ```

9. `nslookup www.google.com`
   - *Output*: 
     ```
     Server:  UnKnown
     Address:  192.168.1.1

     Non-authoritative answer:
     Name:    www.google.com
     Addresses:  2606:4700:3031::ac43:b995
               2606:4700:3037::6818:6cc
               2606:4700:3036::6818:6bc
               2606:4700:3034::ac43:b891
               172.67.185.149
               104.24.108.115
               104.24.109.115
     ```

10. `route -n`
    - *Output*: 
      ```
      Kernel IP routing table
      Destination     Gateway         Genmask         Flags Metric Ref    Use Iface
      0.0.0.0         192.168.1.1     0.0.0.0         UG    0

      0        0 eth0
      169.254.0.0     0.0.0.0         255.255.0.0     U     1000   0        0 eth0
      192.168.1.0     0.0.0.0         255.255.255.0   U     0      0        0 eth0
      ```

11. `arp`
    - *Output*: 
      ```
      Address                  HWtype  HWaddress           Flags Mask            Iface
      gateway                  ether   00:1c:c0:85:2b:40   C                     eth0
      ```

12. `mtr www.google.com`
    - *Output*: 
      ```
      Start: Fri Sep 24 11:32:12 2021
      HOST: your_computer              Loss%   Snt   Last   Avg  Best  Wrst StDev
        1.|-- gateway                   0.0%    10    0.3   0.3   0.3   0.4   0.0
        ...
      ```

Remember, the actual output may vary depending on your network configuration and system setup.

```
