# AzureVM MP 1.0.0.0
Azure VM Properties Management Pack

https://kevinholman.com/2020/07/17/azure-vm-properties-management-pack/

This is a SCOM MP that will discover if your VM is running in Azure, and if so, pull back some interesting and useful properties for grouping, if needed.  You can create SCOM groups based on Azure location, resource group, tags, subscription, etc.

You can read more about the Azure VM metadata here: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/instance-metadata-service

The MP runs a script that will execute a Invoke-WebRequest against the Windows Azure Guest Agent Service Metadata. 
