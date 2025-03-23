<p align="center">
    <img src="./assets/cisco-logo.png" alt="Logo" width="200">
</p>

<h2 align="center">MY-CCNA 200-301 Preparation</h2>

- Cisco Packet Tracer
- Version: 8.0.1.0064

## About this project

I passed my CCNA 200-301 on 17th March 2025.

During my preparation, I built several labs on various networking topics using Cisco Packet Tracer. I hope these labs help you in your CCNA preparation.

## Networking Labs

### [1. VLAN Lab](./1.%20Vlan%20Lab.pkt)

<p align="center">
    <img src="./assets/1. Vlan Lab.png" alt="VLAN Lab">
</p>

A. In this VLAN Lab, 2 VLANs are created: Black & Blue. S3 & S4 are connected with Trunk Links.

B. PC0 - PC2 & PC1 - PC3 can communicate across the switches.

### [2. Routing Lab (Static)](./2.%20Routing%20Lab%20(Static).pkt)

<p align="center">
    <img src="./assets/2. Routing Lab (Static).png" alt="Static Routing & ROAS">
</p>

Static routes have been set up between Router1 & Router0. To communicate between VLAN 10 & VLAN 20, ROAS (Router on a Stick) is implemented.

### [3. Routing Lab (RIP)](./3.%20Routing%20Lab%20(RIP).pkt)

<p align="center">
    <img src="./assets/3. Routing Lab (RIP).png" alt="RIP Routing">
</p>

Router 0, 1, 2 & 3 are connected using RIP (Routing Information Protocol). All three networks (172.18.1.0, 10.2.1.0, 192.168.10.0) can communicate using RIP.

### [4. IPV6 & Floating Routes (Static)](./4.%20IPV6%20%26%20Floating%20Routes%20(Static).pkt)

<p align="center">
    <img src="./assets/4. IPV6 & Floating Routes (Static).png" alt="IPv6 Routing">
</p>

IPv6 addresses are used (2001:0db8:0:0::/64). Static routes are added via Router 15's G0/1/0 interface. A floating route is also configured on Router 15 via interface G0/0.

### [5. OSPF Routing](./5.%20OSPF%20Implementation.pkt)

<p align="center">
    <img src="./assets/5. OSPF Implementation.png" alt="OSPF Routing">
</p>

OSPF is implemented between five routers. Router IDs used: 1.1.1.1, 2.2.2.2, 3.3.3.3, 4.4.4.4, and 5.5.5.5.

### [6. HSRP Setup](./6.%20FHRP%20HSRP%20LAB.pkt)

<p align="center">
    <img src="./assets/6. FHRP HSRP LAB.png" alt="HSRP Setup">
</p>

HSRP (Hot Standby Routing Protocol) is implemented between Router0 & Router1. A virtual router with IP 10.1.1.4 /24 is set up. Router1 is Active while Router0 is Standby, taking over in case of failures.

### [7. 7. AAA Implementation (TACACS+)](./7.%20AAA%20Implementation%20(TACACS%2B).pkt)

<p align="center">
    <img src="./assets/7. AAA Implementation (TACACS+).png" alt="TACACS+ Authentication">
</p>

A simple TACACS+ implementation where the router acts as a TACACS client while the server provides authentication services.

### [8. WLAN WPA2 PSK](./8.%20WLAN%20WPA2%20PSK.pkt)

<p align="center">
    <img src="./assets/8. WLAN WPA2 PSK.png" alt="WPA2-PSK Wireless Network">
</p>

A wireless LAN setup where AP0, AP1 & AP2 connect via a backbone switch. Each AP is running WiFi on different channels to avoid overlapping, with different security configurations.

### [9. ACL Lab](./9.%20ACL%20Lab.pkt)

<p align="center">
    <img src="./assets/9. ACL Lab" alt="Access Control Lists">
</p>

Implementation of Access Control Lists (ACLs) to control traffic. Extended ACLs are deployed.

### [10. STS VPN (GRE Tunnel)](./10.%20STS%20VPN%20(GRE%20Tunnel).pkt)

<p align="center">
    <img src="./assets/10. STS VPN (GRE Tunnel).png" alt="GRE Tunnel">
</p>

A GRE Tunnel is established between Router0 and Router1 to allow secure communication.

<p align="right">
    <b><a href="#">↥ Back To Top</a></b>
</p>

## About Me

- **Koushik Roy**  
- **GitHub**: [github.com/koushikroyfx](https://github.com/koushikroyfx)  
- **LinkedIn**: [linkedin.com/in/koushikroy99](https://www.linkedin.com/in/koushikroy99/)  
- **Twitter**: [x.com/koushikroyfx](https://x.com/koushikroyfx)  
- **Email**: koushikroy05042001@gmail.com  
- **Portfolio**: [koushikroy.in](https://www.koushikroy.in/)  
