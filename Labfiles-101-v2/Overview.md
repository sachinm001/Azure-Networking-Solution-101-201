## Azure Networking Solutions - 101

Azure Networking Solutions provides a fundamental understanding of key networking concepts within the Microsoft Azure cloud platform. This overview serves as a primer for individuals and organizations looking to leverage Azure's networking capabilities to build secure, scalable, and highly available cloud environments.

### Key features of Azure Networking Solutions

  - **Virtual Network:** An Azure Virtual Network (VNet) is a network or environment that can be used to run VMs and applications in the cloud. When it is created, the services and Virtual Machines within the Azure network interact securely with each other, the internet, and on-premises networks.
  - **Virtual Network Gateway:** It is a service used to send encrypted traffic between an Azure virtual network and on-premises locations over the public Internet.
  - **Virtual WAN:** It is a service that brings many networking, security, and routing functionalities together to provide a single operational interface.
  - **DNS Private Resolver:** It is a service that bridges an on-premises DNS with Azure DNS.
  - **Private DNS Zone:** It provides a reliable, secure DNS service to manage and resolve domain names in a virtual network without the need to add a custom DNS solution.
  - **DNS Forwarding Ruleset:** It is a setup with rules pointing to the on-prem dns zone and linked to hub vnet and using the private dns resolver outbound endpoint.



## Hands-on Labs Scenario



## Azure services and related products

  - Virtual Network
  - Virtual Machines
  - Virtual Network Gateway
  - DNS Private Resolver
  - Private DNS Zone
  - DNS Forwarding Ruleset

## Solution Architecture

![sentinel-architecture](../media/sentinel-architecture.png)

## Lab Context

In this Hands-on Lab, you will learn about Azure networking fundamentals. You will get Hands-on experience with Azure resources and how to use networking resources and establish connections from Cloud to On-premise resources.

### Exercise 1: Deploying Azure Sentinel and Onboarding Cloud Resources and Servers

In this exercise, you will deploy the Log Analytics workspace and Microsoft Sentinel and also establish a connection between Windows and M365 data connectors to the Sentinel workspace.

###  Exercise 2: Conducting log analytics and Threat Hunting

In this exercise, you will define a hypothesis in Microsoft Sentinel and create hunts to detect the treats.
