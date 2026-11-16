# Ethernet Switch and ARP Simulation

This project models a small Ethernet network in mCRL2, consisting of three hosts connected through a switch.

It models:
- MAC address learning and frame forwarding by the switch.
- ARP requests, replies, Data exchange and host ARP tables.
- An ARP spoofing scenario, where one host sends frames using a forged source IP address.

Two configurations are included: a normal network with three regular hosts and a scenario where the third host behaves maliciously (`Crazy`) and impersonates the second host's IP address.
