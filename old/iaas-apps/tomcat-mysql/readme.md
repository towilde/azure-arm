# Tomcat & MySQL VMs
Deploy a two tier app environment with Tomcat and MySQL deployed on 2 virtual machines


### Deployed Resources
- Microsoft.Network/virtualNetworks
- Microsoft.Network/publicIPAddresses
- Microsoft.Network/networkInterfaces
- Microsoft.Network/networkSecurityGroups
- Microsoft.Storage/storageAccounts
- Microsoft.Compute/virtualMachines


### Parameters
- `vmSize`:   Size of the VMs to deploy 
- `username`: Linux OS username to login to the VMs
- `sshKey`:   SSH public key file in RSA format 


### Outputs
- `tomcat_url`: URL to access Tomcat
- `ssh_to_tomcat`: Command string to SSH onto Tomcat VM
- `ssh_to_mysql`: Command string to SSH onto Tomcat VM


### Quick Deploy
[![deploy](https://raw.githubusercontent.com/benc-uk/azure-arm/master/etc/azuredeploy.png)](https://portal.azure.com/#create/Microsoft.Template/uri/)

### Notes

