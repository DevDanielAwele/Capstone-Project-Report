# Capstone-Project-Report
Network Design and Emulation for a PCI-DSS Compliant Hadoop Cluster Infrastructure


Network Design and Emulation for a PCI-DSS Compliant Hadoop Cluster Infrastructure

Overview

This repository documents the final-year capstone project of Daniel Obi-Nwosu, completed as part of the Computer Networking Technology Program at Holland College. The project, entitled "Network Design and Emulation for a PCI-DSS Compliant Hadoop Cluster Infrastructure," presents a practical synthesis of regulatory compliance, cloud and on-premise networking, and enterprise-level security engineering.

Purpose and Scope

The project was developed to address the architectural and compliance challenges faced by organisations processing sensitive cardholder data—particularly in the fintech sector. With PCI DSS v4.0.1 as the guiding standard, the report outlines the design and simulation of a scalable, segmented, and secure hybrid infrastructure supporting Hadoop-based analytics.

Daniel’s design spans from physical topology—featuring spine-leaf fabric—to routing strategies that include VRF, OSPF, BGP EVPN, and VXLAN overlays. Cloud integration with Azure was emulated through secure IPSec tunnels, and access controls were meticulously defined via ACLs, AAA systems, and role-based access within Microsoft Active Directory.

Simulation Environment

Cisco Modeling Labs (CML) served as the emulation environment for this project. Despite limitations in virtual machine count, Daniel successfully validated critical security mechanisms, routing behaviour, and segmentation policies, with a focus on protecting the Cardholder Data Environment (CDE).

Research and Citations

References
- Ahamed, M. T., Venkatesh, B., & Samanta, D. (2018). Impact of virtual hadoop cluster
scalability on the performance of big data. International Journal of Computer Applications,
182(38), 25–32. https://doi.org/10.5120/ijca2018917204
BitsPlease. (2020, August 25). VXLAN BGP EVPN- L2VNI (Episode 1) [Video]. YouTube.
https://www.youtube.com/watch?v=faUd0vcRzI8&t
BitsPlease. (2020, August 25). VXLAN BGP EVPN- L3VNI (Episode 2) [Video]. YouTube.
https://www.youtube.com/watch?v=pu21qr3b1GA&list=PLgnrksnL_Rn2GO1RX1-
9T497iDFFwccnb&index
BitsPlease. (2021, February 1). VXLAN BGP EVPN- External connectivity via VRF-LITE
(Episode4) [Video]. YouTube.
https://www.youtube.com/watch?v=VJGucCOHvCQ&list=PLgnrksnL_Rn2GO1RX1-
9T497iDFFwccnb&index
Canadian Centre for Cyber Security. (2024, June 14). Top 10 IT security actions: Number 4 -
Harden operating systems and applications (ITSM.10.090). Government of Canada.
https://www.cyber.gc.ca/en/guidance/top-10-security-actions-number-4-harden-operatingsystems-
and-applications-itsm10090
Cisco Systems. (2022). External connectivity—VRF lite. In Cisco VXLAN BGP EVPN Fabric
Configuration Guide.
https://www.cisco.com/c/en/us/td/docs/switches/datacenter/pf/configuration/guide/b-pfconfiguration/
External-Connectivity-VRF-Lite.pdf
Cisco Systems. (2024). VXLAN BGP EVPN: Design and implementation guide.
https://www.cisco.com/c/en/us/td/docs/dcn/whitepapers/cisco-vxlan-bgp-evpn-design-andimplementation-
guide.html
Cisco. (2025). Cisco modeling labs - personal. Cisco Learning Network Store.
https://learningnetworkstore.cisco.com/cisco-modeling-labs-personal/cisco-modeling-labspersonal/
CML-PERSONAL.html
Edureka. (2020, August 25). What is hadoop cluster? Hadoop cluster setup and architecture
Hadoop training [Video]. YouTube. https://www.youtube.com/watch?v=g4E5kO7ykcE
Gurutech Networking Training. (2022, June 4). Bank network design & implementation part 3 –
Banking network system, enterprise network project 5 [Video]. YouTube.
https://www.youtube.com/watch?v=NLMqmaBvD8Q&t
HandsonERP. (2014, February 15). What is a Hadoop cluster? [Video]. YouTube.
https://www.youtube.com/watch?v=xd9hLHQrjnM
Jeremy’s IT Lab. (2019, October 13). Free CCNA: Network devices, day 1, CCNA 200-301
complete course [Video]. YouTube.
https://www.youtube.com/watch?v=H8W9oMNSuwo&list=PLxbwE86jKRgMpuZuLBivzl
M8s2Dk5lXBQ
Kte’pi, B. (2024). Data analytics. In Salem Press Encyclopedia of Science. Grey House
Publishing.
Louthan, L. (2024, October 21). Working with the PCI DSS 4.0 compliance requirements.
[Video]. LinkedIn Learning. https://www.linkedin.com/learning/working-with-the-pci-dss-
4-0-compliance-requirements/secure-configurations-building-hardening-standards-
18928079
Malone, A. (2020, September 10). NIST and PCI SSC find common ground in development of
software frameworks. PCI Perspectives Blog. PCI Security Standards Council.
https://blog.pcisecuritystandards.org/nist-and-pci-ssc-find-common-ground-indevelopment-
of-software-frameworks
Microsoft. (2024). PCI DSS compliance in Azure. https://learn.microsoft.com/enus/
azure/compliance/offerings/offering-pci-dss
PCI Security Standards Council. (2024). Information supplement: PCI DSS Scoping and
Segmentation Guidance for Modern Network Architectures https://docsprv.
pcisecuritystandards.org/Guidance%20Document/PCI%20DSS%20General/PCI-DSSScoping-
and-Segmentation-Guidance-for-Modern-Network-Architectures.pdf
PCI Security Standards Council. (2024). Payment card industry data security standard:
Requirements and testing procedures, v4.0.1. https://docsprv.
pcisecuritystandards.org/PCI%20DSS/Standard/PCI-DSS-v4_0_1.pdf
Syafrizal, M., Selamat, S. R., & Zakaria, N. A. (2020). Analysis of cybersecurity standard and
framework components. International Journal of Communication Networks and
Information Security (IJCNIS), 12(3). Retrieved February 02, 2025, from
https://www.academia.edu/download/78607584/426.pdf
Venkataramanachary, V., Reveron, E., & Shi, W. (2020). Storage and rack sensitive replica
placement algorithm for distributed platform with data as files. In 2020 12th International
Conference on Communication Systems & Networks (COMSNETS) (pp. 535–538). IEEE.
https://doi.org/10.1109/COMSNETS48256.2020.9027415
