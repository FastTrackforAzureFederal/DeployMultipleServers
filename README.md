# Deploy Multiple Servers on Azure

### Deploy multiple servers within an existing Azure virtual network. Deploy Generation 1 or 2 virtual machines on selected SKU's. Solution options available are Windows Server 2022 Datacenter/2019 Datacenter/2016 Datacenter/2012 R2/Ubuntu 22.04-LTS/ Ubuntu 20.04-LTS/CentOS 7.9.
### Ubuntu 18.04-LTS has been removed since the OS has reached end of life by the vendor.
### The solution is intended for deploying either production or development workloads in Azure Commercial and Azure Government.
### Please note that at the end of the virtual machine name I am appending a "-" and the next ordinal number. Example Server-1, Server-2, etc.
### We are adding a route table, network security group, and availability set for the virtual machines that are being deployed. Please configure these objects as you see fit and associate with either the virtual network or virtual machine. 
### You will also have the ability to choose a data disk of various sizes with a total of 32 disks.
### We are providing the most popular server SKU's available. Please vaidate before using this solution accelerator that the region you are planning on deploying has the virtual machine SKU size. 
### Feel free to use this solution, edit, and add functionality as you see fit. This solution is being provided "as is" for the greater technical community with no guarantees. 
### Use the solution with the Azure portal Custom Template Deployment feature or most common pipeline tools.
### Please enjoy and would love to hear feedback to improve the solution! 

# Deployment Solution Below

### The following template deploys Azure virtual machines on an existing virtual network. The following prerequisite are required; the name of the Azure Resource Group that has the virtual network, the name of the virtual network, and the name of the subnet. 

#### Microsoft Azure Commercial Click Here: ####
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fadelagar%2FDeployMultipleServers%2Fmain%2Fazuredeploy.json)

#### Microsoft Azure Government Click Here: ####

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fadelagar%2FDeployMultipleServers%2Fmain%2Fazuredeploy.json)
