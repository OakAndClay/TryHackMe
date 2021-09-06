# OSI Model

## 7) Application
* Protocols and rules to dictate how the user interacts with the data that is sent or received
    - GUI
    - Browser
    - File Servers

## 6) Presentation
* This is the layer that traslates data into a standard format thaty programs on the application layer can work with.
    - .jpg
    - .pdf
    - .txt

## 5) Session
* Devices establish a connection and begin to transfer data.

## 4) Transport
### Segments
#### TCP - Transport Control Protocol
* Used for tranmitting data that needs to be accurate
* Designed with *reliability* and *guarantee*

#### UCP - User Datagram Protocol
* Faster than TCP
* No guarantee of data transfer
* Ok for things like video streaming. It's no big deal if a couple pixels are missing.

## 3) Network
### Packets
* Determines the optimal path for data to travel from one node to another.
    - Shortest
    - Most Reliable
    - Fastest
* Routing decisions are made based on **IP Addresses**
* Devices that have logic based on IP addresses are known as *layer 3* devices.

#### OSPF - Open Shortest Path First
#### RIP - Routing Information Protocol

## 2) Data Link
### Frames
* Repsonsible for presenting data in a format suitable for tranmission
* Uses MAC address to make routing decisions.
* ARP tables are formed - Assigning IP addresses to device MAC addresses.
* NIC - Network Interface Cards
    -  MAC addresses physically burnt in. Can not be physically changed.

## 1) Physical
### Bits
* This layer consists of the electrical binary signal of 1's and 0's and there medium of transport (ethernet cables)
