# subnetting-class-c-lab
# Subnetting Class C Lab – 192.168.1.0/24

This repository contains a hands-on subnetting lab focused on breaking down a Class C network into four subnets using classless addressing (CIDR). The lab was built and tested using Cisco Packet Tracer.

## 🔍 Lab Objective

To understand and demonstrate subnetting a Class C IP address space and configure essential networking components including routers, switches, DHCP, and client machines.

### 🌐 Network Used
- **Base Network:** 192.168.1.0/24
- **Number of Subnets Created:** 4

---

## 🧪 Lab Tasks and Screenshots

1. **[0 My Topology](./Images/Topology.png)**  
   Visual representation of the full lab setup in Cisco Packet Tracer.

2. **[1 Subnetting Questions](./images/1-subnetting-questions.png)**  
   Calculation and planning of subnet ranges and IP allocation.

3. **[2 Configure Router R1 with IP address](./images/2-router-r1-config.png)**  
   Configuring IP addresses on Router R1 for each subnet.

4. **[3 Configure Switch S1 with IP address](./images/3-switch-s1-config.png)**  
   Assigning management IP to Switch S1.

5. **[4 Configure DHCP Pool](./images/4-dhcp-pool-config.png)**  
   DHCP server configuration to dynamically assign IPs to client devices.

6. **[5 Configure Serial Link on Router 1](./images/5-serial-link-r1.png)**  
   Configuring the WAN serial interface on Router R1.

7. **[6 Configure Serial Link on Internet Router](./images/6-serial-link-internet-router.png)**  
   Connecting R1 to the Internet Router using serial link settings.

8. **[7 Test PC0 for DHCP and Ping](./images/7-pc0-test.png)**  
   Verifying if PC0 received an IP via DHCP and pinging the default gateway.

9. **[8 DNS Traceroute from PC0](./images/8-dns-tracert.png)**  
   Running `tracert` command to resolve and trace the route to DNS.

10. **[9 Test Connection to Web Server](./images/9-web-server-test.png)**  
   Validating if PC0 can reach an external web server (e.g., `www.linkedin.com`).

11. **[10 Subnetting Task in Detail](./images/10-subnetting-detail.png)**  
   Final summary of subnetting strategy, calculations, and assigned IPs.

---

## 💡 What I Learned

- How to subnet a Class C network into multiple smaller networks
- Router and switch IP configuration
- DHCP pool creation and client testing
- WAN and serial link configuration
- DNS and internet connectivity verification from client devices

---

## 🛠 Tools Used

- **Cisco Packet Tracer**
- **Basic command line for ping and tracert**
- **Windows client interface on simulated PC**

---

## 📂 Folder Structure

---

## 🧠 Author

Created by **Qhamaninande Rebe**, as part of my networking fundamentals practice.


