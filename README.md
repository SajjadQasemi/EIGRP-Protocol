# EIGRP-Protocol
EIGRP Multi-AS Redistribution and Internet Access Lab using GNS3/PNETLab.  Includes NAT configuration and static default route advertisement to provide Internet connectivity for all Autonomous Systems.

## 🖥️ Topology

- **AS 153**: Uses IP ranges `172.16.x.x`
- **AS 222**: Uses IP ranges `10.x.x.x`
- **R1 (Edge Router)**: Connects both ASs and provides Internet access via NAT
- **ISP Cloud**: Simulates external Internet connectivity

- ✅ Features
Full EIGRP routing in both AS domains
Redistribution between EIGRP AS 153 and 222
NAT overload for private subnets to access the Internet
Default route propagation to all routers in the topology

📂 Files Included
topology.png → Network diagram
configs/ → Router configuration files
README.md → Documentation

🚀 How to Use
Import the topology into GNS3 or PNETLab.
Apply the provided configurations to the routers.
Test connectivity between subnets and verify Internet access using ping 8.8.8.8.

🔑 Learning Objectives
Understand EIGRP multi-AS scenarios
Practice redistribution between EIGRP processes
Configure NAT and default route for Internet access
Troubleshoot EIGRP and NAT issues in lab environments

Created by Sajjad Qasemi![EIGRP protocol](https://github.com/user-attachments/assets/8c9ab3d7-7070-4def-b3a8-5be9af477c4f)
 for CCNA/CCNP Routing & Switching practice.
