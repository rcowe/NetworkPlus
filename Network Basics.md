# NetworkPlus - Network Basics 

## Understanding Network Geography 
1. PAN - Personal Area Network (around a person)
   1. Example: Phone bluetooth to carplay
2. LAN - Local Area Network (Room or building)
   1. Connecting over wifi to home network
3. CAN - Controller/Campus Area Network (Campus or Business)
4. MAN - Metropolitan Area Network (City or country)
5. WAN - Wide Area Network (Country, worldwide, internet)
   1. Cell modem example for cars

### Wired Network Topology

Physical - cabled and using different types of media 
Logical - Network connection, network flow

Bus Topology:   a single cable where each device taps into by using either a vampire tap 
or a T-connector. Cannot all talk at the same time.

Ring Topology - uses cable running in a circular loop. Cannot all talk at the same time.
- token ring, to prevent collisions when each computer is looking to talk 

FDDI Ring:  use two counter rotating rings for redundancy (when one breaks, the other taked over)
- When states "Ring" = Redundancy; FDDI = Fiber Distributed Data Interface

Challenge with stars is single point of failure/switches when is down, likely 

Hub and Spoke Topology:  Similar to star but with WAN Links instead of LAN connections aCannot all talk at the same time.nd it is used 
for connecting multiple sites

Full Mesh topology = optimal routing is always available as every node connects to very other
node. Full Mesh is expensive due to cabling. Good redundacy. 

Partial Mesh Topology:  hybrid between full mesh and hub-and-spoke. Most businesses use this structure. 
Must consider network traffic patterns. A hybrid or partial mesh network combines features from a mesh and star topology 
to provide a network that is more redundant than a star topology but less redundant than a full mesh topology

Peer-to-peer: A peer-to-peer network model does not differentiate between the clients and the servers, 
and every node can become a client and a server when requesting and responding to service requests.

### Wireless Networks 

Infrastructure Mode: uses a wireless access point as a centralized point and supports wireless security controls

Adhoc Mode: Decentralized wireless network which creates P2P connections and does not require a router or access point

Wireless Mesh Topology: Interconnection of different types of nodes, devices or radios. This creates redundant and reliable
connections. Ideal for post natural disasters. 

### IOT - Internet of Things 

802.11:  WiFi, wireless networks that can operate in infrastructure mode or adhoc mode

Bluetooth: Low energy use variant of bluetooth which allows for a mesh network 

RFID (Radio Frequency ID): Uses electromagnetic fields to read data stored in embedded tags. EX: hotel keys.
Radio-frequency identification (RFID) uses electromagnetic fields to automatically identify and track tags 
attached to objects. The warehouse could utilize RFID to allow for the accurate scanning of items using radio 
frequency tracking tags and sending data of up to 2 KB to a sensor at rapid speeds.

Near Field Communication (NFC): Enables two devices to communicate within a 4-cm range. EX: paying with phone, samsung pay, apple pay

Infrared (IR): Operates with line of sight. EX: Remote for TVs

Z-Wave: Provides short range low latency data transfer with slower rates and less power consumption than Wi-Fi. Used for home automation

ANT+: Collection and transfer of sensory data. EX: tire pressure system in car, mainly sensory data. 




