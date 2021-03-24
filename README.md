﻿# Azure question bank
 
Q1. Difference between private endpoint and service endpoint!

Ans. The following definition of Azure Private Endpoint has been taken from Microsoft Azure documentation:

**"Azure Private Endpoint is a network interface that connects you privately and securely to a service powered by Azure Private Link. Private Endpoint uses a private IP address from your VNet, effectively bringing the service into your VNet. The service could be an Azure service such as Azure Storage, Azure Cosmos DB, SQL, etc. or your own Private Link Service."**

Private endpoint enables connectivity between the consumers from the same VNet, regionally peered VNets, globally peered VNets and on premises using VPN or Express Route and services powered by Private Link.

*The private endpoint must be deployed in the same region as the virtual network*.
<hr/>

Q2. What is a proximity group and in what scenario it is used?

Q3. Difference between application gateway and load balancer!

Q4. How to define gates in Azure devops release pipeline?

Q5. What kinds of poilicies are there in Azure APIM?

Q6. When do Azure APIM policies execute?

Q7. What sort of database migration challenges have you faced ever?

Q8. What services could be known as Azure native?

Q9. What is Shared Access Signature and how to generate it?

Q10. Difference between NIC and NSG?

Q12. How to set NSG rules through Terraform?

Q13. What is Azure Web Application Firewall and how does it used with Applicaiton Gateway, Front Door and CDN?

Q14. What is a WAF policy and to whom it can be associated?

Q15. What is a Mutex Lock and how does it work?

Q16. How Api gateway vs Front Door

Q17. How do you decide to go with SQL Server vs CosmosDB

Q18. What is CAP theorem?

Ans. CAP theorem is also called Brewer’s theorem, named after the computer scientist, Eric Brewer.
We need to understand the distibuted system as it is base requirement of CAP.

**
CAP theorem stands for:

Consistency
Availability
Partition tolerance
**

Consistency means all the users can see the same data at same time.

Availability means the system continues to operate even in the presence of node failure.

Partition tolerance means the system continues to operate in spite of network failures.

<hr/>

Q19. What are the power states of an Azure Virtual Machine?
Ans. 
There are total 7 power states
1. Starting: Indicates that the VM is being started.
2. Running: Indicates that the VM is running.
3. Stopping: Indicates that the VM is being stopped.
4. Stopped: Indicates that the VM is stopped. Note that VMs in the stopped state still incur compute charges.
5. Deallocating: Indicates that the VM is being deallocated.
6. Deallocated: Indicates that the VM is completely removed from the hypervisor but still available in the control plane. VMs in the deallocated state do not incur compute charges.
7. Unknown (-): Indicates that the power state of the VM is unknown. 

<hr/>

