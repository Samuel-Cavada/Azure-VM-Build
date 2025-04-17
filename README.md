# Azure VM Build

# Project Objective
-Here you want to outline your project objective/goal - 

Building a Comprehensive SIEM Solution. My goals are to centralize log collection, correlation, and analysis, enabling proactive threat detection, incident response, and improved overall cybersecurity posture.The project aims to provide real-time visibility into security events and enhance incident response capabilities.

# Tools 
-List of tools used within the project-
e.g. Azure

# Skills Gained
-List and explain the skills. Show why they are key for Cyber Security-

Security Architecture - Developed a holistic security architecture that considered the entire system, addressing weaknesses and ensuring a cohesive security strategy.

# Outcomes 
- Talk about what you achieved, use screenshots!-

# Walkthrough

### ✅ Step 1: [Adding a Resource to Azure Group]

> _Once in your resource group, you can click on the 'Create Resource' button to open the resource marketplace._
> 
![ Image 1](images/1.jpg "CREATING A NEW RESOURCE INSIDE YOUR RESOURCE GROUP")


> 
### ✅ Step 2: [Adding a Resource to Azure Group]

> _Once in your resource group, you can click on the 'Create Resource' button to open the resource marketplace._

![Step 2](images/2.jpg "Step 2 - Navigate to Resource Groups")

> 
### ✅ Step 3: [Basics Tab]

> _In the Basics tab, you can configure essential settings for your Azure Virtual Machine, such as the subscription, resource group, and VM name._
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

> _In the Disk tab, you can configure the storage options for your Azure Virtual Machine._

![Step 4](images/4.jpg "Step 4 - Click Create Resource")


> 
### ✅ Step 5: [Disk tab]

> _Once in your resource group, you can click on the 'Create Resource' button to open the resource marketplace._
<!--
![Step 5](images/5.jpg "Step 5 - Disk tab")
-->

> 
### ✅ Step 6: [Management tab]

> _Once in your resource group, you can click on the 'Create Resource' button to open the resource marketplace._

- No need to modify anything on this page.
  
![Step 6](images/6.jpg "Step 6 - Management tab")


> 
### ✅ Step 7: [Monitoring tab]

> _Once in your resource group, you can click on the 'Create Resource' button to open the resource marketplace._

- **[S]** Disable boot diagnostics as it will increase boot-up time.
- **[T]** Review and create the VM.

![Step 7](images/7.jpg "Step 7 - Monitoring tab")



> 
### ✅ Step 8: [Azure Virtual Machine Review Page]

> _Once in your resource group, you can click on the 'Create Resource' button to open the resource marketplace._

-  Review and create the VM.

![Step 8](images/8.jpg "Step 8 - Azure Virtual Machine Review Page")


> 
### ✅ Step 9: [Azure Virtual Machine Deployment Confirmation Page]

> _Once in your resource group, you can click on the 'Create Resource' button to open the resource marketplace._

![Step 9](images/9.jpg "Step 9 - Azure Virtual Machine Deployment Confirmation Page")


> 
### ✅ Step 10: [Azure Resource Group Homepage]

> _Once in your resource group, you can click on the 'Create Resource' button to open the resource marketplace._
>
![Step 10](images/10.jpg "Step 10 - Azure Resource Group Homepage")
