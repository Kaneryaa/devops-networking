# Computer networking basics 
Computer networking involves the interconnection of various devices and systems to enable them to communicate and share resources. Here are some basic components and concepts in computer networking

## Components
Devices:

Computers: These can be desktops, laptops, servers, or any device capable of running networking software.
Switches and Routers: These are critical devices for directing network traffic. Switches connect devices within a local area network (LAN), while routers connect different networks and manage traffic between them.
Network Interface Cards (NICs):

NICs are hardware components that allow devices to connect to a network. They provide a physical connection to the network medium (like Ethernet cables or Wi-Fi).
Cabling and Connectors:

Ethernet Cables: These are commonly used for wired network connections. They come in different categories (e.g., Cat5e, Cat6, Cat6a) which determine their speed and bandwidth capabilities.
Fiber Optic Cables: These use light signals to transmit data and are capable of high-speed, long-distance communication.
Wireless: Wi-Fi is a common wireless networking technology that allows devices to connect without physical cables.
Network Protocols:

Protocols are rules that govern how data is transmitted, received, and formatted in a network. Examples include TCP/IP (Transmission Control Protocol/Internet Protocol), HTTP (Hypertext Transfer Protocol), and FTP (File Transfer Protocol).
IP Addresses:

IP addresses uniquely identify devices on a network. IPv4 and IPv6 are the two main versions of the Internet Protocol in use today.
Subnetting:

Subnetting involves dividing a network into sub-networks to improve performance, security, and manageability.
Network Topologies:

Topology refers to the physical or logical layout of a network. Common topologies include bus, star, ring, and mesh.
LAN and WAN:

LAN (Local Area Network): A network limited to a small geographic area, like a single building or a campus.
WAN (Wide Area Network): Spans a large geographic area, often connecting multiple LANs across cities or countries.
Firewalls and Security Devices:

Firewalls control the incoming and outgoing network traffic based on an applied rule set. They are a critical component for network security.
DNS (Domain Name System):

DNS translates human-readable domain names (like www.example.com) into IP addresses that machines can understand.
DHCP (Dynamic Host Configuration Protocol):

DHCP automatically assigns IP addresses to devices on a network, making it easier to manage large networks.
Gateway:

The gateway is a device that connects a local network to the internet. It serves as an entry and exit point for data traffic.
These are some fundamental components and concepts in computer networking. Understanding these basics is crucial for setting up and managing networks effectively.
## OSI Models 
## Classification 
## Devices 
## Home Network 
## IP Adress 
## Protocol 
## DNS & DHCP

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
