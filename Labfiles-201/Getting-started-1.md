## **Getting Started with Azure Networking 201**
 
Welcome to your Azure Networking 201 workshop! We've prepared a seamless environment for you to explore and learn about Azure services. Let's begin by making the most of this experience:

## Overview

In this exercise, you'll log in to the Azure Portal and review the pre-deployed resources that are part of the lab environment.

## Instructions
 
## **Accessing Your Lab Environment**
 
Once you're ready to dive in, your virtual machine and lab guide will be right at your fingertips within your web browser.
 
![](../media/y175.png)

## **Virtual Machine & Lab Guide**
 
Your virtual machine is your workhorse throughout the workshop. The lab guide is your roadmap to success.
 
## **Exploring Your Lab Resources**
 
To get a better understanding of your lab resources and credentials, navigate to the **Environment Details** tab.
 
![](../media/y176.png)
 
## **Utilizing the Split Window Feature**
 
For convenience, you can open the lab guide in a separate window by selecting the **Split Window** icon at the bottom right corner.

![](../media/y177.png)
 
## **Managing Your Virtual Machine**
 
Feel free to start, stop, or restart your virtual machine as needed from the **Resources** tab. Your experience is in your hands!
 
![Manage Your Virtual Machine](../Images/res.png)
 
## **Let's Get Started with Azure Portal**
 
1. On your virtual machine, click on the Azure Portal icon as shown below:
 
    ![](../Labfiles-101-v2/Media/161.png)

1. You'll see the **Sign into Microsoft Azure** tab. Here, enter your credentials:
 
   - **Email/Username:** <inject key="AzureAdUserEmail"></inject>
 
    ![](../Labfiles-101-v2/Media/162.png)
 
1. Next, provide your password:
 
   - **Password:** <inject key="AzureAdUserPassword"></inject>
 
   ![](../Labfiles-101-v2/Media/163.png)
 
1. If prompted to stay signed in, you can click **No**.

    ![](../Labfiles-101-v2/Media/164.png)
 
1. If a **Welcome to Microsoft Azure** pop-up window appears, simply click **Maybe Later** to skip the tour.


1. You should see this list of pre-deployed resource groups with resources that will be used in this lab:

     ![](../media/y178.png)

   - **Onprem-RG-<inject key="DeploymentID" enableCopy="false"/>**: On-premises related resources, vNets, Lab-VM (with DNS role and Telnet client enabled), DB-VM (with SQL Express or MySQL) and Virtual Network Gateway.

     ![](../Labfiles-101-v2/Media/102-1.png)

   - **Prod-RG-<inject key="DeploymentID" enableCopy="false"/>**: Workload related: vm-Prod vNets, spoke1VM, spoke2VM, storage account etc.

      ![](../Labfiles-101-v2/Media/102-2.png)

   - **Prod-RG2-<inject key="DeploymentID" enableCopy="false"/>**: Workload related: GatewayVnet, spoke3VM, spoke4VM, VPN, Log Analytics workspace, Local network gateway etc.
    
      ![](../media/y179.png)
      
   - **Sharedservices-RG-<inject key="DeploymentID" enableCopy="false"/>**: Core network infrastructure related: virtual WAN and its related resources, VPN Gateway, DNSresolvevnet.

      ![](../Labfiles-101-v2/Media/102-3.png)
    
1. Now, click on **Next** from the lower right corner to move to the next page.


## Summary

In this exercise, you signed in to the Azure Portal and reviewed the pre-deployed resource groups.

Now you're all set to explore the powerful world of technology. Feel free to reach out if you have any questions along the way. Enjoy your workshop!