# Create a VM from a specialized VHD disk
"https%3A%2F%2Fraw.githubusercontent.com%2Ffjuhasz%2Fattila%2Fmaster%2Fazuredeploy.json
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffjuhasz%2FCustomVM%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

## Prerequisite 
- VHD file that you want to create a VM from already exists in a storage account.

```
NOTE

This template will create an additional Standard_GRS storage account for enabling boot diagnostics each time you execute this template. To avoid running into storage account limits, it's best to delete the storage account when the VM is deleted.
```

This template creates a VM from a specialized VHD. The VHD file can be located in a storage account using a tool such as Azure Storage Explorer http://storageexplorer.com/
The soruce of this tempalte is 
<a href=" https://github.com/Azure/azure-quickstart-templates/tree/master/201-vm-specialized-vhd>
</a>


