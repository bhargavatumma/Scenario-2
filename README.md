# Scenario-2

Macro Life, a healthcare company has recently setup the entire Network and Infrastructure on Azure.
The infrastructure has different components such as Virtual N/W, Subnets, NIC, IPs, NSG etc.
The IT team currently has developed PowerShell scripts to deploy each component where all the
properties of each resource is set using PowerShell commands.
The business has realized that the PowerShell scripts are growing over period of time and difficult to
handover when new admin onboards in the IT.
The IT team has now decided to move to ARM based deployment of all resources to Azure.
All the passwords are stored in a Azure Service known as key Vault. The deployments needs to be
automated using Azure DevOps using IaC(Infrastructure as Code).
1) What are different artifacts you need to create - name of the artifacts and its purpose
2) List the tools you will to create and store the ARM templates.
3) Explain the process and steps to create automated deployment pipeline.
4) Create a sample ARM template you will use to deploy a Windows VM of any size
5) Explain how will you access the password stored in Key Vault and use it as Admin Password in the VM
ARM template.
