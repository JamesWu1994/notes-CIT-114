# 7.01 What is a Network?
* The internet is tens of thousands kilometres of fiber optic cable, hundreds of thousands to millions of kilometres of copper wire, and hardware and software connecting them all together in a redundant, fast, and self-sufficient network.
* At its core, a **computer network** is just two or more client machines that are connected together, using a network device, to share resources.
* A network can be logically partitioned to create subnets.
* A router or switch are used to connect the clients together and enable communications.
## Basic Networking Concepts Part 1
## Basic Networking Concepts Part 2

# 7.02 Definitions for Computer Networking
## Computer Network
* It is the interconnection of multiple devices, generally termed as Hosts connected using multiple paths for the purpose of sending/receiving data or media.
* There are also multiple devices or mediums which helps in the communication between two different devices which are known as **Network devices**.
* The layout pattern using which devices are interconnected is called as **network topology**.

## OSI
**OSI** stands for Open Systems Interconnection and is a reference model that specifies standards for communications protocols and also the functionalities of each layer.
It includes:
  * **Layer 7 - Application** - The application layer is the OSI layer closest to the end user, which means both the OSI application layer and the user interact directly with the software application.
  * **Layer 6 - Presentation** - The presentation layer establishes context between application-layer entities, in which the application-layer entities may use different syntax and semantics if the presentation service provides a mapping between them.
  * **Layer 5 - Session** -
The session layer controls the dialogues (connections) between computers. It establishes, manages and terminates the connections between the local and remote application.
  * **Layer 4 - Transport** -
The transport layer provides the functional and procedural means of transferring variable-length data sequences from a source to a destination host, while maintaining the quality of service functions.
  * **Layer 3 - Network** -
The network layer provides the functional and procedural means of transferring variable length data sequences (called packets) from one node to another connected in "different networks".
  * **Layer 2 - Data Link** -
The data link layer provides node-to-node data transfer—a link between two directly connected nodes
  * **Layer 1 - Physical** -
Responsible for the transmission and reception of unstructured raw data between a device and a physical transmission medium.
Protocol
## Protocol
* Is the set of rules or algorithms which define the way how two entities can communicate across the network and there exists different protocol defined at each layer of OSI model.

## Unique Identifiers of Network
* **Host name** -Each device in the network is associated with a unique device name known as Hostname.

## IP Address (Internet Protocol address)
* Also, know as Logical Address, is the network address of the system across the network.
* To identify each device in the world-wide-web, Internet Assigned Numbers Authority (IANA) assigns IPv4 (Version 4) address as a unique identifier for each device on the Internet.
* However there is also an IPv6 (Version 6) scheme available that has more addresses available.
* Length of the IPv4 address is 32-bits. (Hence we have 2^32 IP addresses available.)

## Classless Inter-Domain Routing (CIDR)

The CIDR address is expressed as follows:

* An IP address (which is the first address of the network)
* Next, a slash character (/)
* Finally, a number that tells you how many bits of the routing prefix must be fixed or allocated for the network identifier

There are two special cases:

* Fixed IP addresses, in which every bit is fixed, represent a single IP address (for example, 192.0.2.0/32). This type of address is helpful when you want to set up a firewall rule and give access to a specific host.
* The internet, in which every bit is flexible, is represented as 0.0.0.0/0

## MAC Address (Media Access Control address)
* Also known as physical address, is the unique identifier of each host and is associated with the NIC (Network Interface Card).
* MAC address is assigned to the NIC at the time of manufacturing.
* Length of the MAC address is : 12-digit/ 6 bytes/ 48 bits

## Port

* Port can be referred to as a logical channel through which data can be sent/received to an application.
* Any host may have multiple applications running, and each of this application is identified using the port number on which they are running on.

## Socket
* The unique combination of IP address and Port number together are termed as Socket.

## DNS Server
* DNS stands for Domain Name System.
* DNS is basically a server which translates web addresses or URL (ex: www.google.com)

## ARP
* ARP stands for Address Resolution Protocol.
* It is used to convert the IP address to its corresponding Physical Address(i.e.MAC Address).
* ARP is used by the Data Link Layer to identify the MAC address of the Receiver’s machine.

## RARP
* RARP stands for Reverse Address Resolution Protocol.
* As the name suggests, it provides the IP address of the device given a physical address as input.
* But RARP has become obsolete since the time DHCP has come into the picture.

## The Internet
* In simplest words, it is a global network of smaller networks interconnected using communication protocols that are standardized.
* The Internet standards describe a framework known as the Internet protocol suite.
* This model divides methods into a layered system of protocols.
* These layers are as follows:
 * Application layer (highest) — concerned with the data(URL, type, etc), where HTTP, HTTPS, etc comes in.
 * Transport layer — responsible for end-to-end communication over a network.
 * Network layer — provides a data route.

## The World Wide Web
* The web a subset of the internet. It’s a system of Internet servers that support specially formatted documents. The documents are formatted in a markup language called HTML(that supports links, multimedia, etc). These documents are interlinked using hypertext links and are accessible via the Internet.
* To link hypertext to the Internet, we need:

 * The markup language, i.e., HTML.
 * The transfer protocol, e.g., HTTP.
 * Uniform Resource Locator (URL), the address of the resource.
 * We access the web using web browsers.

## URI
* URI stands for ‘Uniform Resource Identifier’, it’s like an address providing a unique global identifier to a resource on the Web. Uniform Resource Locator (URL) is the most commonly used form of a URI.

* The URL consists mainly of two parts:

 * The protocol used in the transfer, e.g., HTTP.
 * The domain name.

# 7.03 Introduction to IP Addresses & Binary Math
## IP addresses and DNS
