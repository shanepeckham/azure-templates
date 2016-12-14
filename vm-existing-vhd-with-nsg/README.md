# Create a VM from a specialized VHD disk

## Prerequisites 
- VHD file that you want to create a VM from already exists in a storage account.

```
NOTE

This template will create an additional Standard_LRS storage account for enabling boot diagnostics each time you execute this template.
```

This will build an App Service API to retrieve a simple contact list

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

This template creates a VM from an existing VHD. The VHD file can be copied into a storage account using a tool such as Azure Storage Explorer http://storageexplorer.com/
