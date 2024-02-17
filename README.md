# XYZ Company Branch Network Design

## Project Description

XYZ Company, a fast-growing company in Eastern Australia, is opening a branch near the local village of Bonalbo. They require a separate network for the branch operations, distinct from the headquarters. As a young network engineer hired for the task, the goal is to design and implement the branch network to meet the company's requirements efficiently.

## Requirements

1. **Networking Equipment:**
   - One Cisco router and one Cisco switch to be used.
   - All networking products are CISCO.

2. **Departments:**
   - Admin/IT
   - Finance/HR
   - Customer Service/Reception

3. **VLAN Configuration:**
   - Each department to have a dedicated VLAN.
   - VLAN segregation for:
     - Admin/IT
     - Finance/HR
     - Customer Service/Reception

4. **Wireless Network:**
   - Each department requires a wireless network for users.

5. **IP Addressing:**
   - Host devices to obtain IPv4 addresses automatically.

6. **Inter-Department Communication:**
   - Devices in all departments should be able to communicate with each other.

7. **ISP Network:**
   - Base network provided by ISP: 192.168.1.0/24.

## Technologies Implemented

- Simple network design using a router and access layer switch.
- Correct cabling for connecting networking devices.
- VLAN creation and port assignment for departmental segregation.
- Subnetting and IP addressing for efficient network allocation.
- Inter-VLAN routing using the router-on-a-stick method.
- DHCP server configuration on the router.
- WLAN configuration for wireless network access using Cisco Access Point.
- Host device configurations for automatic IP address assignment.
- Testing and verifying network communication.

## Additional Notes

- The network topology has been created to satisfy the user requirements and has been verified and tested to ensure functionality.

## Network Topology



<br/>

![scenario](https://github.com/YuklidD/Cisco_pkt_project2/blob/main/Company%20Networking%20.jpg)
