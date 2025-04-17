# Azure Virtual Machine Deployment

# Project Objective

The main aim of this project is to establish a secure and efficient Azure Virtual Machine environment. This involves configuring VM settings, ensuring robust data encryption, and optimizing network security to support tasks such as remote access and cybersecurity operations.

# Tools 

- Azure Portal: For creating and managing virtual machines.
- Azure Key Vault: To securely store and manage encryption keys.
- Azure Network Security Groups: To control inbound and outbound traffic to the VM.
- Remote Desktop Protocol (RDP): For remote access to the VM.

# Skills Gained

- Azure VM Configuration: Learn how to set up and configure virtual machines in Azure.
- Data Encryption: Understand the importance of encryption and how to implement it using platform-managed keys.
- Network Security: Gain insights into configuring network security groups and managing traffic.
- Remote Access Management: Develop skills in setting up secure remote access to virtual machines.

# Outcomes 

By the end of this project, I successfully created a secure and efficient Azure Virtual Machine. I gained valuable skills in configuring VMs, managing encryption keys, and implementing network security measures. Additionally, I developed proficiency in setting up remote access and learned best practices for cybersecurity, enhancing my ability to conduct vulnerability assessments and threat hunting activities.

# Walkthrough

### ✅ Step 1: [Adding a Resource to Azure Group]

> _Once in your resource group, you can click on the 'Create Resource' button to open the resource marketplace._
> 
![ Image 1](images/1.jpg "CREATING A NEW RESOURCE INSIDE YOUR RESOURCE GROUP")


> 
### ✅ Step 2: [Azure Marketplace]

> _Once in your resource group, click on the 'Create Resource' button to open the Azure Marketplace._

![Step 2](images/2.jpg "Step 2 - Azure Marketplace")

> 
### ✅ Step 3: [Basics Tab]

> _In the Basics tab, configure essential settings for your Azure Virtual Machine, such as the subscription, resource group, and VM name._
- **[A]** Select the appropriate subscription. I had to select the one that had my resource group in it.
- **[B]** Select the appropriate resource group. I was given this resource group.
- **[C]** Create the name of your virtual machine.
- **[D]** Select the region according to my time zone.
- **[E]** Keep this as is.
- **[F]** Keep this as is.
- **[G]** Trusted launch virtual machine: This offers secure boot, vTPM, and boot integrity to ensure a secure boot-up.
- **[H]** Select the OS you want.
- **[I]** Select standard-ds1-v2 vCPU, 3.5 GiB memory ($41.61/month). - Cheaper option.
- **[J]** Create a username and password. Make sure that it is at least 15 characters or longer with special characters, lowercase, and uppercase to ensure it is secure.
- **[K]** If you want to be able to remote into via RDP, then turn this on. I will, as I will use this virtual machine to conduct vulnerability management and threat hunting and other cybersecurity projects.
- _Go to the next tab: Disks_

![Step 3](images/3.jpg "Step 3 Basics Setup")


> 
### ✅ Step 4: [Disk Tab]

> _In the Disk tab, configure the storage options for your Azure Virtual Machine._

- **[L]** Select the desired OS disk size.

- **[M]** Select the desired disk type.

- **[N]** Enabling platform-managed keys for the OS disk ensures automatic encryption (at rest)

- _Go to the next tab: Network_

![Step 4](images/4.jpg "Step 4 - Click Create Resource")


> 
### ✅ Step 5: [Disk tab]

> _In the Networking tab, configure the network settings for your Azure Virtual Machine._

- **[O]** Select the appropriate virtual network. 

- **[P]** Select the appropriate subnet.


- **[Q]** Select this option only if you are okay with having a public IP address. This will increase the chance of exposure and also be a target for malicious attacks from the network.

- **[R]**

- _Go to the next tab: Management_
  
![Step 5](images/5.jpg "Step 5 - Disk tab")


> 
### ✅ Step 6: [Management tab]

> _In the Management tab, configure the management settings for your Azure Virtual Machine._

- No need to modify anything on this page.

- _Go to the next tab: Monitoring_
  
![Step 6](images/6.jpg "Step 6 - Management tab")


> 
### ✅ Step 7: [Monitoring tab]

> _In the Monitoring tab, configure the monitoring settings for your Azure Virtual Machine._

- **[S]** Disable boot diagnostics as it will increase boot-up time.
  
- **[T]** Review and create the VM.

- _Go to the next page: Review + Create_

![Step 7](images/7.jpg "Step 7 - Monitoring tab")



> 
### ✅ Step 8: [Azure Virtual Machine Review Page]

> _Review all the settings and create the VM._

-  Review and create the VM.

- _Go to the next page: Create_

![Step 8](images/8.jpg "Step 8 - Azure Virtual Machine Review Page")


> 
### ✅ Step 9: [Azure Virtual Machine Deployment Confirmation Page]

> _Confirm the deployment of your Azure Virtual Machine._

- _Go to the next page: Go To Resource_

![Step 9](images/9.jpg "Step 9 - Azure Virtual Machine Deployment Confirmation Page")


> 
### ✅ Step 10: [Azure Resource Group Homepage]

> _Return to the Azure Resource Group homepage.._
>
![Step 10](images/10.jpg "Step 10 - Azure Resource Group Homepage")
