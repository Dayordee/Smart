# Lab 3: Manage Packages and Services on a Linux VM (Azure or AWS)


1. Create a Linux VM
2. Install the Apache Web Server
3. Start the service status via command line
4. Investigate the service status via command line
5. Stop the service


Challenge: Create a boostrapping script that will install and start this service on new EC2 VMs

Notes:

Install and Configure Apache (Ubuntu)

https://ubuntu.com/tutorials/install-and-configure-apache#1-overview
How to install Apache on RHEL 8 / CentOS 8 Linux

https://linuxconfig.org/installing-apache-on-linux-redhat-8
How to use cloud-init to customize a Linux virtual machine in Azure on first boot

https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-automate-vm-deployment
Create bootstrap actions to install additional software

https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-plan-bootstrap.html

1. I created a linux Virtual machine
![](../Screenshots/Screenshot%20(400).png)

2. I launched my Apache server 
![](../Screenshots/Screenshot%20(401).png)
![](../Screenshots/Screenshot%20(402).png)

3. I started my service via commandline
![](../Screenshots/Screenshot%20(404).png)

4. I investigated the service via commandline
![](../Screenshots/Screenshot%20(405).png)

5 I stoppped the service
![](../Screenshots/Screenshot%20(406).png)