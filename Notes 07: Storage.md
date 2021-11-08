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
