# Packet-Tracer-Project-One-Router-Three-LANs-IPv4-addressing-interface-bring-up-validation-
Cisco IOS basics: interface configuration, subnetting (/8, /16, /24), device IP setup, persistent save, and ICMP reachability tests


# Description/ Tools used
What this lab demonstrates

IPv4 addressing across three different prefix lengths (/8, /16, /24)

Cisco IOS interface configuration (ip address, description, no shutdown)

Host IP configuration on endpoints

Operational verification with show ip interface brief and ICMP pings

Persisting configuration with write memory

# key commands used
show ip interface brief
conf t
interface gi0/0 | gi0/1 | gi0/2
 description ...
 ip address A.B.C.D MASK
 no shutdown
end
write memory
show running-config
