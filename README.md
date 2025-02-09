# Cisco-Networking-Project
#### Network project using Cisco

You have created a Cisco network project, designing and configuring a network topology with multiple subnets. The network has a main IP address of 147.227.155.0/24, and the subnets are allocated to cover different infrastructure segments.

The topology includes routers, switches, servers (DHCP, DNS, WEB), and network devices such as computers, laptops, and a wireless access point. You have segmented the network based on the needs of each subnet, optimizing IP address allocation, routing, and connectivity.

To complete this project, you had to fulfill several technical requirements, including:

Designing the network and correctly connecting cables
Subnetting the given IP range and ensuring efficient address allocation
Assigning static IP addresses and configuring DHCP for dynamic IP allocation
Setting up default gateways and verifying inter-network connectivity via pinging
Configuring routing (static or dynamic using RIP)
Setting up and using DNS and a web server, ensuring accessibility from any machine
Using minimal IP classes for inter-router connections
Implementing NAT for network address translation
Demonstrating the ability to explain any aspect of the implementation
This project can be used for simulating a corporate network, testing routing configurations, and setting up essential network services. It showcases a solid understanding of network design, IP addressing, routing, and server configurations.

![image](https://github.com/user-attachments/assets/54cf04d5-57e0-41bb-a39f-6b39c50d6874)


IP: 147.227.155.0 = 10010011.11100011.10011011.00000000

Mask: 255.255.255.0=11111111.11111111.11111111.00000000  /24


[0...63] [.64....127] [.128....159] [.160....191] [.192....199] [.200....207] [.208....211] [.212....215] [.216....219] [.220....223] [.224....227] [.232....239] 

  N1/26 &nbsp;&nbsp;&nbsp;  N2/26 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; N3/27 &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; N4/27 &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; N5/29  &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; N6/29 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  N7/30 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  N8/30 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; N9/30 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   N10/30 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; N11/30 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  N12/29


Server DHCP: 147.227.155.2

Server WEB: 147.227.155.66

Server DNS: 147.227.155.130
