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

📚 References
- Ahamed, M. T., Venkatesh, B., & Samanta, D. (2018). Impact of virtual Hadoop cluster scalability on the performance of big data. International Journal of Computer Applications, 182(38), 25–32. https://doi.org/10.5120/ijca2018917204

- BitsPlease. (2020, August 25). VXLAN BGP EVPN- L2VNI (Episode 1) [Video]. YouTube. 

- BitsPlease. (2020, August 25). VXLAN BGP EVPN- L3VNI (Episode 2) [Video]. YouTube. 
  
- BitsPlease. (2021, February 1). VXLAN BGP EVPN- External connectivity via VRF-LITE (Episode4) [Video]. YouTube.
  
- Canadian Centre for Cyber Security. (2024). Top 10 IT security actions: Harden operating systems and applications. https://www.cyber.gc.ca/en/guidance/top-10-security-actions-number-4-harden-operating-systems-and-applications-itsm10090

- Cisco Systems. (2022). External connectivity—VRF lite. In Cisco VXLAN BGP EVPN Fabric Configuration Guide. https://www.cisco.com/c/en/us/td/docs/switches/datacenter/pf/configuration/guide/b-pfconfiguration/External-Connectivity-VRF-Lite.pdf

- Cisco Systems. (2024). VXLAN BGP EVPN: Design and implementation guide. https://www.cisco.com/c/en/us/td/docs/dcn/whitepapers/cisco-vxlan-bgp-evpn-design-andimplementation-guide.html

- Cisco. (2025). Cisco modeling labs - personal. Cisco Learning Network Store. https://learningnetworkstore.cisco.com/cisco-modeling-labs-personal/cisco-modeling-labspersonal/CML-PERSONAL.html

- Edureka. (2020). What is a Hadoop cluster? YouTube

- Gurutech Networking Training. (2022). Bank network design & implementation YouTube
  
- HandsonERP. (2014). What is a Hadoop cluster? YouTube

- Jeremy’s IT Lab. (2019). Free CCNA: Network devices, Day 1 YouTube

- Kte’pi, B. (2024). Data analytics. In Salem Press Encyclopedia of Science.

- Louthan, L. (2024). Working with the PCI DSS 4.0 compliance requirements. LinkedIn Learning

- Malone, A. (2020). NIST and PCI SSC in Software Frameworks. PCI SSC Blog

- Microsoft. (2024). PCI DSS compliance in Azure. https://learn.microsoft.com/en-us/azure/compliance/offerings/offering-pci-dss

- PCI Security Standards Council. (2024).

- Scoping and Segmentation Guidance. https://docsprv.pcisecuritystandards.org/Guidance%20Document/PCI%20DSS%20General/PCI-DSS-Scoping-and-Segmentation-Guidance-for-Modern-Network-Architectures.pdf

- PCI DSS Requirements and Testing Procedures v4.0.1. https://docsprv.pcisecuritystandards.org/PCI%20DSS/Standard/PCI-DSS-v4_0_1.pdf

- Syafrizal, M., Selamat, S. R., & Zakaria, N. A. (2020). Analysis of cybersecurity standard and framework components. IJCNIS, 12(3). PDF

- Venkataramanachary, V., Reveron, E., & Shi, W. (2020). Storage and rack-sensitive replica placement algorithm. COMSNETS 2020, IEEE. https://doi.org/10.1109/COMSNETS48256.2020.9027415
