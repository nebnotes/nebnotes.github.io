<center> <u> <h1> Networking and Telecommunication </h1> </u> </center>

> Telecommunication is the exchange of data or instruction over a distance using signals or electromagnetic waves.

- Devices used in telecommunication systems are known as nodes.

> Data communication is the telecommunication which involves computers and computer network.

## Data Transmission/Communication Mode:

> Transmission mode refers to way in which data communication occurs based on direction of transfer.

- There are three modes:
    - Simplex: Transmission of data takes place in a single direction. E.g: Radios, Televisions etc.
    - Half Duplex: Transmission of data takes place in both directions but only one direction at a time.
    - Full Duplex: Transmission of data can take place in both direction simultaneously.

## Components of data communication:

- Message: Data/information that is to be communicated
- Sender: Computer/Computing device that creates and sends the message
- Receiver: Computer/Computing device that receives the message
- Medium: Channel/path through which message is transferred
- Protocol: Set of rules followed by sender and receiver.

## Communicaton/Transmission Media

> A channel or path through which data and information are transmitted between connected devices in a network environment is called communication media.

- Two types:
    - Guided / Wired / Bounded
    - Unguided / Wireless / Unbounded

### Guided Transmission Media

> Guided transmission media uses cable or wire to transfer data and information among computers.

- Types:
    - Co-axial (BNC connector)
    - Twisted pair (RJ-45 connector)
    - Fiber Optics (ST, SMA, SC connectors)

<div style="page-break-after: always;"></div>

#### Co-Axial Cable

> Consists of a inner conductor surrounded by an insulating layer and again surrounded by conducting shield. 

- Advantages:
    - Higher bandwidth as compared to twisted pair
    - Better shielding
    - Good noise resistance
    - Lower error rates
- Disadvantages:
    - More expensive than twisted pair

#### Twisted Pair Cable

> Consists of multiple pair of copper wires twisted together and insulated with plasic. 

- Types:
    - Unshielded Twisted Pair: These don't have a metallic shield/sheath.
    - Unshielded Twisted Pair: These have a metallic shield/sheath.

- Advantages:
    - Relatively easy to implement and terminate
    - Least expensive

- Disadvantages:
    - Poor noise immunity
    - High attenuation
    - Lower bandwidth

#### Fiber Optic Cable

> Made up of plastic or glass fiber to transmit data.

- Advantages:
    - High bandwidth and Fast
    - low power loss
    - Longer distance support
    - Good resistance
    - Low attenuation

- Disadvantages:    - 

    - Most Expensive
    - Difficult to join (splice)
    - Easily breakable

## Unguided transmission media

> Unguided transmission media doesn't use wire or cable for data transmission.

- Types:
    - Radio Wave
    - Micro Wave
    - Satellite Communication

### Radio wave

> High frequency wave(30MHz to 1GHz) wave that can travel long distance.

- Data is changed to signal with FM(Frequency modulation), AM(Amplitude modulation) and PM(Phase Modulation)

### Microware

> Super High Frequency wave(1GHz to 40GHz) wave that can travel short distance(30 to 40KHz) and need repeaters.

- Needs tall towers

### Satellite Communication

> Uses artificial satellite stationed in space for this specific purpose.

- Earth station communicates with the satellite.


### Other unguided mediums

- Infrared: short range, used in remotes
- Bluetooth: short range, used for short range communication (mostly to connect peripherals). (2.4GHz)

<div style="page-break-after: always;"></div>

## Computer Network

> Computer network is a group of two or more computers and devices connected to each other through wired or wireless media to share resources.

- Advantages:
    - Can be used to share hardware(printer, storage devices etc.).
    - Can be used to share data and software.
    - Can be used to communicate.
    - Supports central control and administration.

- Disadvantages:
    - Malware can be transferred.
    - Skilled manpower is required to setup and manage.
    - Initial setup cost is high.
    - Cybercrimes can occur and need to be handled.

### Elements/Componentts of Computer Network

- Hardware Components:
    - Computer System:
        - Server: Provides service/resources and controls and manages other computers on the network
            - File Server
            - Database Server
            - Print Server
            - Network Server
            - Mail Server etc.
        - Workstation: Uses resources of the network
    - Network Adapter/NIC card: Network Interface card provides ports to connect computer to network. In can come built-in or needs to be placed on expansion slot on motherboard.
    - Connectors: Used to connect communication media with network devices.(BNC, RJ-45, ST)
    - Network devices: Devices used for setting up network like hub, switch etc.

<div style="page-break-after: always;"></div>

## Network Devices

### Hub

> Networking device with multiple port that transmits received data to all connected computers including sender.
    - Passive hub: No electricity and no amplification.
    - Active hub: Requires electricity and amplifies signal

### Switch
> Networking device with multiple port that can determine source and destination of data packets.

- Switch is upgrade of hub.

> Hub is cheaper but it is less efficient and slower as it broadcasts packets to all connected computers and is half duplex.

### Bridge

> Bridge connects two networks with similar/same protocol.

- Bridge inspects incoming signals (MAC address) and decides whether to forward or discard it making it efficient.

### Gateway

> Gateway connects two networks having different protocol. 

- It is like a dedicated server that acts as protocol converter. 

### Router

> Router joins multiple wired or wireless networks together and routes(determine path and send) data based on IP address.

### Repeater

> Repeater is a network connectivity device that regenerates/amplifies weak signals.

### MODEM

> Modulator Demodulator is a network device that transfers data through telephone wire.

- Modulation: Conversion of digital signals to analog signals.
- Demodulation: Conversion of analog signal to digital signal.

- Modulation is required as telephone wire can only transfer analog signal and demodulation is required as computers understand digital signal.

<div style="page-break-after: always;"></div>

## Network Topology

> Network topology is the inter-connection pattern of network components.

- Types:
    - Bus topology
    - Ring Topology
    - Star Topology
    - Mesh Topology

### Bus Topology

> This topology uses a segmeent of single cable to connect nodes. This cable is called bus. 

- Terminators are attached at start and end.

- Advantages:
    - Easy to setup
    - Easy to expand
    - Cheap
    - Easy to understand

- Disadvantages:
    - Single point of failure(If main cable breaks, whole network malfunctions)
    - Network performance degrades with heavy traffic.

### Ring/Loop Topology

> In this topology, a closed loop is formed by computers. 

- Data is transmitted in one direction(clockwise or anticlockwise).

- Advantages:
    - Cheap to install and expand.
    - Each computer acts as client or server.
- Disadvantage: 
    - If a node fails, whole network is disturbed. 
    - Difficult to troubleshoot.
    - Adding or removing node disturbs the network.

<div style="page-break-after: always;"></div>

### Star Topology

> Type of topology in which all nodes are connected to a central device (hub/switch) through a cable.

- Advantage:
    - Fast
    - Easy to troubleshoot
    - Easy to setup and modify
    - Node failure doesn't disturb network

- Disadvantages:
    - Initial cost is high due to hub/switch.
    - If hub/switch fails, network fails.

### Mesh Topology

> In this each computer is connected to every other computer.

- Advantage:
    - Fast
    - Privacy is maintained

- Disadvantages:
    - Requires lot of wires
    - Not practical for large number of devices.

> Hybrid topology can be made by combining different topology. 

## Types of Computer Network(Based on size)

- Three types:
    - Local Area Network: Small network limited within a small area like a room, a building, school, college etc. Eg. A buildings CCTV network.
    - Metropolitan Area Network: Network mostly within cities and is used for sharing of regional resources. Eg. Traffic light network of a city.
    - Wide Area Network: Very large network that covers country, countries or even the world. Eg. Internet.

<div style="page-break-after: always;"></div>

## Network Architecture/Model

> Network Architecture specifies how computers on the network interact and communicate with each other.

- Types:
    - **Client-Server Model**: There is at least one server that provides services and some clients/workstations that receive service from server. Servers are usually powerful computers and can administer the network and share resources.
    - **Peer to Peer Model**: There is no server that manages the network or share resources. Each computer connected is called `peer` and each per has equal rights.
    - **Centralized Network Model**: Here all client nodes are entirely dependent on the central server. 

> Peer to Peer models are easy to set up but lack security, need individual hardware and software, and have limited expansion and network performance.

> Centralized Network save a lot of resource and are highly secure and administerd but have single point of failure.

## Internet and its services

> Internet is a WAN that connects computers all over the work based on TCP/IP protocol suite.

- Services of Internet:
    - **WWW**: Interlinked collection of hypertext documents and multimedia contents available on internet.
    - **Email**: Used to send and receive messages electronically throught the Internet.
    - **Telnet**: Allows user to use a remote computer through internet.
    - **FTP**: Protocol that lets file transmission between computers on the internet.
    - **Search Engine**: Communication program that finds documents based on keywords. Eg. Google.
    - **IRC**: Allows real time communication.
    - **Online Banking**: Financial transactions through internet.
    - **E-commerce**: Bying and Selling of products through internet.

---