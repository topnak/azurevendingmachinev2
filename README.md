# azurevendingmachinev2
This is repository for Azure Vending Machine for year FY 2023

App Info:
- Application is running based on "Power App" Platform - you will require Power App premium due to premium connector is required for APIM
- Application is prototype
- Application's aim is to 
  - Provide application for non-IT user to be able to order "Virtual machine" to be used for their application
  - Help accelerate the process to approve new resource in Azure
  
Deploy App
- Power App using import feature on Power App studio
- Power Automate using import feature on Power Automate (Flow)
- APIM at least using "Developer tier"  - Do not use consumption tier because it can not pinpoint "IP address" so we cannot limit ip address access
- Azure logic app consumption is used for this solution and block access to limit to only APIM access
- Azure storage can be used and can use SAS as key
- Azure DevOps (hasnt been implemented yet)
- Azure Communication is setup for US region - as Email service is currently only available for US region for Global usage


If any question, please put in comment section.
