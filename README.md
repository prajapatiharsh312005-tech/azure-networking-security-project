# Azure Networking & Security

## Project Overview
This project demonstrates fundamental Azure networking and security concepts by creating a Virtual Network, two subnets, and a Network Security Group (NSG) with an inbound HTTP rule.

## Azure Resources
- **Resource Group:** `rg-azure-network-security`
- **Virtual Network:** `vnet-cloud-security-01`
- **Web Subnet:** `snet-web`
- **Application Subnet:** `snet-app`
- **Network Security Group:** `nsg-web-security`
- **Inbound Rule:** `Allow-HTTP`

## Architecture
The Virtual Network contains separate web and application subnets. The NSG is associated with the web subnet and contains a rule allowing inbound TCP traffic on port 80.

## Implementation Steps
1. Created a dedicated Azure resource group.
2. Created a Virtual Network.
3. Configured web and application subnets.
4. Created a Network Security Group.
5. Added an inbound rule allowing TCP port 80 with priority 100.
6. Associated the NSG with the web subnet.
7. Reviewed configuration and Azure subscription costs.

## Skills Demonstrated
- Azure Virtual Networks (VNet)
- IPv4 addressing and subnetting
- Network Security Groups (NSG)
- Inbound security rules and rule priorities
- Azure resource management and cost awareness

## Validation
Verified the subnet configuration, NSG association, and inbound security rule in the Azure Portal.

**Note:** This project demonstrates network configuration. No virtual machine or public web server was deployed, so end-to-end HTTP connectivity was not tested.

## Cost Management
Reviewed the Azure subscription's reported cost. Costs may be delayed, so ongoing billing should be monitored.

## Learning Outcome
Gained practical experience configuring Azure network segmentation and controlling traffic with NSG rules.
