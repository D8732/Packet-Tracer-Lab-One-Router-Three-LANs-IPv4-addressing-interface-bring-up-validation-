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


 Show ip interface brief shows interfaces down before being configured
<img width="627" height="96" alt="Interfaces command" src="https://github.com/user-attachments/assets/8de133f2-f465-4a52-bfff-534368e03cd2" />

Configure Gigabit g0/0, g0/1 g0/2
<img width="632" height="218" alt="Gigabit0" src="https://github.com/user-attachments/assets/8d42be44-ea35-48d7-a7c7-f622d7a59d18" />
<img width="637" height="332" alt="Gigabit1" src="https://github.com/user-attachments/assets/eaaf8145-32ab-435a-aa22-7da21cfd7522" />
<img width="633" height="469" alt="Gigabit2" src="https://github.com/user-attachments/assets/ea4f3252-b783-4592-a9f8-3655775edcd1" />

