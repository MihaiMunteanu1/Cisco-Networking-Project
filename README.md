# Cisco-Networking-Project
#### Network project using Cisco

I have created a Cisco network project, designing and configuring a network topology with multiple subnets. The network has a main IP address of 147.227.155.0/24, and the subnets are allocated to cover different infrastructure segments.

The topology includes routers, switches, servers (DHCP, DNS, WEB), and network devices such as computers, laptops, and a wireless access point. I have segmented the network based on the needs of each subnet, optimizing IP address allocation, routing, and connectivity.

To complete this project, I had to fulfill several technical requirements, including:

* Designing the network and correctly connecting cables

* Subnetting the given IP range and ensuring efficient address allocation

* Assigning static IP addresses and configuring DHCP for dynamic IP allocation

* Setting up default gateways and verifying inter-network connectivity via pinging

* Configuring routing (static or dynamic using RIP)

* Setting up and using DNS and a web server, ensuring accessibility from any machine

* Using minimal IP classes for inter-router connections

* Implementing NAT for network address translation

This project can be used for simulating a corporate network, testing routing configurations, and setting up essential network services. It showcases a solid 
understanding of network design, IP addressing, routing, and server configurations.

![image](https://github.com/user-attachments/assets/54cf04d5-57e0-41bb-a39f-6b39c50d6874)


IP: 147.227.155.0 = 10010011.11100011.10011011.00000000

Mask: 255.255.255.0=11111111.11111111.11111111.00000000  /24

N1/26: [0...63]  
N2/26: [64...127]  
N3/27: [128...159]  
N4/27: [160...191]  
N5/29: [192...199]  
N6/29: [200...207]  
N7/30: [208...211]  
N8/30: [212...215]  
N9/30: [216...219]  
N10/30: [220...223]  
N11/30: [224...227]  
N12/29: [232...239]  

Server DHCP: 147.227.155.2

Server WEB: 147.227.155.66

Server DNS: 147.227.155.130
