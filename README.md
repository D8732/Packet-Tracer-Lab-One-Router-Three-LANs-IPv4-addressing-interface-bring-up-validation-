# Packet Tracer Project One Router Three LANs IPv4 addressing interface bring up validation
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

# Show ip interface brief shows interfaces down before being configured

<img width="627" height="96" alt="Interfaces command" src="https://github.com/user-attachments/assets/8de133f2-f465-4a52-bfff-534368e03cd2" />

# Configure Gigabit g0/0, g0/1 g0/2

<img width="632" height="218" alt="Gigabit0" src="https://github.com/user-attachments/assets/8d42be44-ea35-48d7-a7c7-f622d7a59d18" />
<img width="637" height="332" alt="Gigabit1" src="https://github.com/user-attachments/assets/eaaf8145-32ab-435a-aa22-7da21cfd7522" />
<img width="633" height="469" alt="Gigabit2" src="https://github.com/user-attachments/assets/ea4f3252-b783-4592-a9f8-3655775edcd1" />


# All interfaces all interfaces up after being Configured

<img width="600" height="66" alt="showipbrief" src="https://github.com/user-attachments/assets/5cc46305-8c9f-4cb5-9d04-b4957b493fb8" />

# Show Running Config

<img width="332" height="165" alt="sh config" src="https://github.com/user-attachments/assets/28139955-5560-40e2-ba3b-d9a586ace3b6" />

<img width="320" height="224" alt="shconfig" src="https://github.com/user-attachments/assets/5c7407d9-7fcc-433d-9cac-15de665c827c" />

# Save Configuration

<img width="207" height="60" alt="Save config" src="https://github.com/user-attachments/assets/a9690955-a664-4846-8c8d-3357447d9031" />


# Statically Configure end host with Ip address then test ping command for connectivity

<img width="677" height="304" alt="Setip" src="https://github.com/user-attachments/assets/7f2e8ae7-8de0-4f87-b0a0-55186c73239f" />

<img width="1067" height="299" alt="ping to Pc2" src="https://github.com/user-attachments/assets/184d76f2-7b5d-454a-b650-7424f4cf78d0" />

