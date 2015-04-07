![](https://ci.appveyor.com/api/projects/status/m4aedx4vslshgpo7?svg=true)

####What is it?

An [Appease](http://appease.io) task template that sets an [Azure App Service plans](http://azure.microsoft.com/en-us/documentation/articles/azure-web-sites-web-hosting-plans-in-depth-overview/) number of workers.

####How do I install it?

```PowerShell
Add-AppeaseTask `
    -DevOpName YOUR-DEVOP-NAME `
    -TemplateId SetAzureAppServicePlanNumberOfWorkers
```

####What parameters are required?

#####Name
description: a `string` representing the name of the App Service plan.

#####ResourceGroupName
description: a `string` representing the name of the resource group this App Service plan will be added to.

#####NumberOfWorkers
description: an `int` representing the number of worker VMs allocated to the App Service plan
