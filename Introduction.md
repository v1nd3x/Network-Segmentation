# Network Segmentation

Network segmentation is a network security technique that divides a network into smaller, distinct sub-networks that enable network teams to compartmentalize the sub-networks and deliver unique security controls and services to each sub-network.

## Flat Networks vs. Segmented Networks

**Flat network** refers to an architecture where all devices can connect to each other without going through any other hardware.
Flat networks provide fast and reliable connectivity for all connected devices, and security efforts generally concentrate on isolating internal networks from external networks

![image](https://user-images.githubusercontent.com/59384064/201025931-d2e8eb38-7f09-41c2-87ca-beda96da6ce0.png)

**Flat Network Architecture** 

- attackers successfully compromise the network, they might be able to move laterally, from one system to another, potentially gaining access to more sensitive systems.


**Network segmentation** is a powerful but underutilized security measure, and it is one of the cornerstones of a successful information security program.

![image](https://user-images.githubusercontent.com/59384064/201026221-15d491e9-5a45-4f67-b8c6-0a2ed5605249.png)

**Segmented Network Architecture** 
- if properly implemented and managed, can greatly limit lateral movement.

## The reasons for using network segmentation include the following:

   	- Gigantic networks are broken into smaller, easier-to-manage segments.
    - Network administrators can set up granular and separate policies for each subnet.
    - Administrators can control, manage or restrict the flow of traffic between subnets.
    - User congestion is relieved on other parts of the network.
    - Cybersecurity improves in limiting how far a malicious attack can spread by confining the attack to one segment.

|     |     |
| --- | --- |
|  Network Segmentation | Micro segmentation |
| - Traditional network segmentation covers a larger segment of the network. <br>- Network segmentation works with the physical network.<br>- Network segmentation policies are broad.<br>- Network segmentation is hardware-based.<br>- Network segmentation limits north-south traffic at the network level | - Micro segmentation can be used at the device level, which makes it great for internet of things (IoT) and edge devices.<br>- Micro segmentation is for virtual networks.<br>- Micro segmentation policies are much more granular.<br>- Micro segmentation is typically software-based.<br>- Micro segmentation limits east-west traffic at the workload level. |

   [Next Topic - Resources](https://github.com/v1nd3x/Network-Segmentation/blob/main/Resources.md)
