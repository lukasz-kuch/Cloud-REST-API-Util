# MID-Server-API-Client
ServiceNow application for SN developers to debug the `MID Server script includes` in a very simple way. You just call `MID Server script include` and executes it using the available `MidServer`. This application allows you to send API Requests directly to the cloud client (as it works like for `POSTMNA` or `INSOMNIA`), so you can check all scripts and returned responses. It is very helpful when creating a new `MID Server script include`, checking what will return, compare the result with API's response.

MidServer Script Include functionality works based on OOTB ServiceNow Cloud API Base Script Include (e.g AzureCloudAPIBase, AWSCloudAPIBase, etc.)

##  Requirements
* running MID Server that has access to a cloud environment
* Cloud Service Account (e.g. Azure AWS, VMWARE...)
