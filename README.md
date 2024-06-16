# Hospital-networking-system-using-Cisco-Packet-Tracer
Design of a hospital networking system using Cisco Packet Tracer, featuring essential facilities like female wards, reception desk, chemist, server room, doctor cabins, parking, and testing labs.

Hospital Network Setup Overview:

Reception Desk:
At the reception desk, PC6 and PC7 are configured with IP addresses 192.168.1.82/28 and 192.168.1.83/28 respectively, both using a subnet mask of 255.255.255.240. They connect to PT Switch3 via straight-through cables. PT Switch3 is linked to ROUTER0-1841 through Fast Ethernet 0/1 with IP address 192.168.1.81/28, serving as the gateway for PC6 and PC7.

Parking Area:
In the parking area, PC8 and PC9 are assigned IP addresses 192.168.1.114/28 and 192.168.1.115/28 respectively, with a subnet mask of 255.255.255.240. They are connected to PT Switch4 via straight-through cables. PT Switch4 connects to ROUTER2-1841 through Fast Ethernet 0/0 with IP address 192.168.1.113/28, acting as the gateway for PC8 and PC9 to send data to the server room.

Chemist Department:
The chemist department features PC0 and PC1 with IP addresses 192.168.1.2/28 and 192.168.1.3/28 respectively, using a subnet mask of 255.255.255.240. They connect to PT Switch0 via straight-through cables, and PT Switch0 connects to ROUTER0-1841 through Fast Ethernet 0/0 with IP address 192.168.1.1/28, serving as the gateway for PC0 and PC1.

Server Room:
The server room hosts two PT Servers: Server0 with IP address 192.168.1.98/26 and Server1 with IP address 192.168.1.99/26, both using a subnet mask of 255.255.255.192. They connect to PT Switch5, which is linked to ROUTER1-1841 through Fast Ethernet 0/1 with IP address 192.168.1.97/28, serving as the gateway for both servers.

Network Infrastructure:

    Each department's PCs are connected to respective PT switches.
    PT switches are connected to routers (ROUTER0-1841, ROUTER1-1841, ROUTER2-1841) which act as gateways for different segments of the hospital network.
    All critical data from departments flows to the servers in the server room, ensuring centralized storage and accessibility across the hospital.

This setup ensures efficient data management, secure connectivity, and reliable access to hospital records and services throughout the facility.
