Every electronic device has IP addesses -> when we search anything -> **Network interface receives that data and It ask DNS server to resolve the destination IP** -> DNS server **will provide the destination IP to the network interface** -> Now our device knows the destination IP -> **NI will send the data from local network to the internet through the gateway if firewall allows** -> **once data explore to the internet it should pass though different NI of their routers** -> once data reaches destination IP -> destination will process the requested data and sends back in same process.  **in this whole process data may transfer using TCP/UDP protocal**. 

TCP is reliable it through the success/unsuccessful message, so that we can send again. it transfers data in order. UDP is unreliable but fatser than TCP it won't display success/failure message.

## Network Interface
**Purpose** -> sends or receives the data

**Types** -> Ethernet (WIred) / Wifi (wireless)       ## some devices may have more Network interfaces

**Network Manager** -> software utility used for to configure and manage network interfaces. It will be available both in GUI and CMI. 


### Commands
IP Address -> **ip a | ip addr | ip addr show | ifconfig | hostname -I**
