# IaaSWksp

1) Create a Virtual Network 
https://azure.microsoft.com/en-us/documentation/articles/virtual-networks-create-vnet-arm-pportal/
An Azure virtual network (VNet) is a representation of your own network in the cloud. You can control your Azure network settings and define DHCP address blocks, DNS settings, security policies, and routing.

Create a Network Security Group
https://azure.microsoft.com/en-us/documentation/articles/virtual-networks-create-nsg-arm-pportal/
You can use an NSG to control traffic to one or more virtual machines (VMs), role instances, network adapters (NICs), or subnets in your virtual network. An NSG contains access control rules that allow or deny traffic based on traffic direction, protocol, source address and port, and destination address and port. 

2) Create a lab in Azure DevTest Labs 
https://azure.microsoft.com/en-us/documentation/articles/devtest-lab-create-lab/
Azure DevTest Labs enables you to specify key policies that help you to control cost and minimize waste in your labs. These lab policies include the maximum number of VMs created per user and per lab, and various auto-shutdown and auto-start options.

Set Lab Policies
https://azure.microsoft.com/en-us/documentation/articles/load-balancer-get-started-internet-portal/
Azure DevTest Labs enables you to specify key policies that help you to control cost and minimize waste in your labs. These lab policies include the maximum number of VMs created per user and per lab, and various auto-shutdown and auto-start options.


3) Create User Defined Routes in Network
https://azure.microsoft.com/en-us/documentation/articles/virtual-network-create-udr-arm-ps/
Although the use of system routes facilitates traffic automatically for your deployment, there are cases in which you want to control the routing of packets through a virtual appliance. You can do so by creating user defined routes that specify the next hop for packets flowing to a specific subnet to go to your virtual appliance instead, and enabling IP forwarding for the VM running as the virtual appliance.
Pre Req - Install and Configure Azure PowerShell https://azure.microsoft.com/en-us/documentation/articles/powershell-install-configure/

Creating an Internet-facing load balancer 
https://azure.microsoft.com/en-us/documentation/articles/load-balancer-get-started-internet-portal/
Create a load balancer that receives network traffic on port 80 and send load-balanced traffic to virtual machines "web1" and "web2"
Create NAT rules for remote desktop access/SSH for virtual machines behind the load balancer
Create health probes
