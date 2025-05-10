# Virtualization - Virtual Private Cloud using Azure

### Aim :
To design and implement a secure, scalable, and highly available Azure Virtual Network (VNet) infrastructure that enables seamless communication between cloud-based resources and on-premises systems, while ensuring compliance with organizational security and networking standards.

### Problem Statement :
Modern cloud applications need secure, isolated, and scalable networks for reliable communication and data protection. Without a properly configured Azure Virtual Network (VNet), resources face security risks and connectivity issues. Organizations struggle to design networks that meet performance, security, and compliance needs.

### Design Steps :
1. Sign in to the Azure Portal
	Navigate to https://portal.azure.com and log in with your Azure account credentials.
  <img width="699" alt="image" src="https://github.com/user-attachments/assets/cf58295f-7593-413d-8046-2ee83470f0da" />

2. Navigate to Virtual Networks
	In the left-hand menu, click Create a resource or search for Virtual networks in the search bar.
	Select Virtual network and click Create.

  <img width="770" alt="image" src="https://github.com/user-attachments/assets/80c57de5-323d-4720-af75-8d887ff26a24" />

3. Configure Basic Settings
	Subscription: Choose your Azure subscription.
	Resource Group: Select an existing resource group or create a new one .
	Name: Enter a name for the VNet .
	Region: Select the Azure region .

  <img width="614" alt="image" src="https://github.com/user-attachments/assets/9825f3e0-9070-42f4-912c-da0a93645263" />

4. Configure Security Settings (Optional)
	DDoS Protection: Enable Azure DDoS Protection Standard for defence against DDoS attacks.
	Firewall: Enable Azure Firewall for centralized network traffic filtering, or skip if not needed.

  <img width="772" alt="image" src="https://github.com/user-attachments/assets/08ae94dc-5331-4808-b721-46986f7d8e0c" />

5. Define IP Address Space
	IPv4 address space: Specify a private IP range.
	Subnet: Add at least one subnet:
                	Name: default or custom name.
        	Address range: A subset of the VNet range.

  <img width="478" alt="image" src="https://github.com/user-attachments/assets/9046cf9d-0c0d-4fe6-ad72-537d600862b7" />

6. Add Tags (Optional)
	Add key-value pairs for resource organization (e.g., Environment: Production).

  <img width="664" alt="image" src="https://github.com/user-attachments/assets/6598e3b8-baab-46c8-ac1e-9973410a4254" />

5. Review and Create
	Review the configuration details.
	Click Create to provision the VNet. Deployment typically takes a few minutes.

  <img width="663" alt="image" src="https://github.com/user-attachments/assets/7fec9e0a-28d7-413f-9fb8-ed1149b6091a" />

### Output : 
<img width="623" alt="image" src="https://github.com/user-attachments/assets/a826a838-cb23-4122-9afe-f15380c3b5d5" />

### Result : 
A secure and scalable Azure Virtual Network (VNet) was implemented, enabling isolated communication between cloud resources. Integration with on-premises infrastructure was achieved via a VPN gateway, with security enforced through Network Security Groups (NSGs). The network met performance, accessibility, and compliance standards, resulting in a production-ready environment.








