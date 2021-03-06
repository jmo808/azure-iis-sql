# IIS VMs and SQL VM

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjmo808%2Fazure-iis-sql%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png" />
</a>

This template creates one or two Windows Server 2012R2 VM(s) with IIS configured using DSC. It also installs one SQL Server 2014 standard edition VM, a VNET with two subnets, NSG, load balancer, a Jump Box and probing rules.

It also configures a Recovery Vault with a long term backup policy and crash consistent backups on all the VM's.

## Resources
The following resources are created by this template:
- 1 or 2 Windows 2012R2 IIS Web Servers.
- 1 Jump Box for remote administration
- 1 SQL Server 2014 running on premium or standard storage.
- 1 virtual network with 3 subnets and NSG rules.
- 1 Availability Set for IIS servers.
- 1 Load balancer
- 1 Recovery Vault
- 1 Backup Policy

