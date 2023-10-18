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

## DNS & DHCP
## Network Command 

To take user inputs in Python, you can use the `input()` function. By default, `input()` returns a string, so you'll need to convert it to the desired data type (int, float, or string) using `int()`, `float()`, or leave it as is.

Here's an example code that takes user inputs in different data types:

```python
# Taking an integer input
user_input_int = int(input("Enter an integer: "))

# Taking a floating-point input
user_input_float = float(input("Enter a float: "))

# Taking a string input
user_input_string = input("Enter a string: ")

# Printing the inputs
print(f"You entered an integer: {user_input_int}")
print(f"You entered a float: {user_input_float}")
print(f"You entered a string: {user_input_string}")
```
