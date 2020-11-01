# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

The CMS app is very small app does not require too much processing power.The price for deploy this app would be less in case of app service and VM both. The appservice is PAAS and provides very nice UI from Azure portal for deploying and configuring the app. Real time logs, monitoring of the app can be easily done using Azure portal. With the app service user has gets rids from the complexity for deploying a app what we get in a VM. 

As the app service is a managed service. It provides a better SLA over a VM. 

I have chosen the Azure App Service to host the app as CMS app is small app and needs only python 3.8 as run time stack.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If the complexity of the app increases and requires more compute power and more languages in run time stack. I would deploy the app to VM