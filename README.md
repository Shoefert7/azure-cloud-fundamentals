# azure-cloud-fundamentals
☁️ Cloud Computing Fundamentals & Azure Infrastructure

Course: NETW 211 – Fundamentals of Cloud Computing
Author: Shawn Hoefert
Date: December 2023
📌 Project Overview

This project demonstrates foundational skills in cloud computing by deploying, configuring, and managing virtual infrastructure within Microsoft Azure. It covers key concepts such as Virtual Machines (VMs), Virtual Networks (VNets) and subnets, Network Security Groups (NSGs), cloud storage, and cloud monitoring with alert notifications. The project emphasizes practical application of cloud services for building and securing basic cloud environments.
🎯 Key Objectives

    Virtual Machine Deployment & Management: Successfully deploy and connect to Windows and Linux Virtual Machines in Azure.

    Network Segmentation: Design and implement Virtual Networks (VNets) with segmented subnets to organize cloud resources.

    Network Security Configuration: Configure Network Security Groups (NSGs) to control inbound and outbound network traffic to VMs, enhancing security.

    Cloud Storage Operations: Utilize Azure Blob Storage for file management, including uploading, accessing, and understanding access tiers and versioning.

    Cloud Monitoring & Alerting: Set up Azure Monitor action groups and alert rules to notify on VM status changes, demonstrating proactive operational awareness.

    Connectivity Verification: Verify network connectivity between VMs and external hosts using command-line tools (ipconfig, ping).

🔧 Tools & Technologies

    Cloud Platform: Microsoft Azure

    Virtualization: Azure Virtual Machines (VMs)

    Networking: Azure Virtual Networks (VNets), Subnets, Network Security Groups (NSGs)

    Storage: Azure Blob Storage (Hot, Cool, Cold, Archive tiers; Blob Versioning)

    Monitoring: Azure Monitor (Action Groups, Alert Rules)

    Operating Systems: Windows Server, Ubuntu Linux

    Command-Line Tools: ipconfig, ping, ssh (for Linux VM access)

    Concepts: IP Addressing, Subnetting, Network Access Control, Cloud Security Principles, Resource Groups.

🔄 Workflow Summary

This project involved a series of hands-on exercises within the Azure environment:

    Azure VM Deployment: Launched and configured Virtual Machines (Windows Server and Ubuntu Linux) within Azure.

    VM Connectivity: Established secure connections to VMs via RDP (for Windows) and SSH (for Linux), and verified internal network configurations.

    VNet & Subnet Creation: Designed and implemented a Virtual Network with multiple subnets to logically segment cloud resources.

    Inter-VM Connectivity Testing: Performed ping tests between VMs residing in different subnets to verify network routing.

    Network Security Group (NSG) Configuration: Created and applied NSG rules to control traffic flow to VMs, specifically demonstrating how to allow/deny ICMP (ping) traffic.

    Cloud Storage Management: Uploaded files to Azure Blob Storage, accessed them via URL, and explored different storage access tiers and blob versioning for data lifecycle management.

    Cloud Monitoring Setup: Configured Azure Monitor action groups and alert rules to trigger email notifications upon specific VM events (e.g., VM restart, deallocation), showcasing proactive monitoring capabilities.

    Alert Testing: Validated the functionality of configured alerts by intentionally triggering VM state changes and confirming notification delivery.

📈 Skills Demonstrated

    Cloud Computing: Practical experience with core cloud services and infrastructure management in Azure.

    Network Configuration: Proficiency in setting up and securing virtual networks, subnets, and network access controls.

    Virtualization: Hands-on experience deploying and managing virtual machines.

    Cloud Security: Understanding and implementation of security best practices for cloud resources (NSGs, access tiers, monitoring).

    System Administration: Basic administration tasks on Windows and Linux VMs (e.g., ipconfig, ssh).

    Problem-Solving & Troubleshooting: Diagnosing and verifying network connectivity issues.

    Data Management: Familiarity with cloud storage solutions and data versioning.

    Monitoring & Alerting: Ability to configure and test cloud-based monitoring solutions for operational awareness.
