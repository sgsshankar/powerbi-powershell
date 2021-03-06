# Microsoft Power BI PowerShell samples

## Introduction

This repo contains samples for calling the Power BI REST APIs using PowerShell. Each PowerShell script is self-documenting.

* [manageRefresh.ps1](https://github.com/Azure-Samples/powerbi-powershell/blob/master/manageRefresh.ps1) - trigger scheduled refresh and check refresh history

* [rebindReport.ps1](https://github.com/Azure-Samples/powerbi-powershell/blob/master/rebindReport.ps1) - clone a report in the Power BI service and rebind it to a different dataset

* [copyWorkspace.ps1](https://github.com/Azure-Samples/powerbi-powershell/blob/master/copyWorkspace.ps1) - duplicate a workpsace in the Power BI service 

* [bindtogateway.ps1](https://github.com/Azure-Samples/powerbi-powershell/blob/master/bindtogateway.ps1) - Binds a dataset to a new gateway.

* [takeover-dataset.ps1](https://github.com/Azure-Samples/powerbi-powershell/blob/master/takeover-dataset.ps1) - Takes ownership of a dataset to your account.

* [Zero-Downtime-Capacity-Scale.ps1](https://github.com/Azure-Samples/powerbi-powershell/blob/master/Zero-Downtime-Capacity-Scale.ps1) - scale Power BI Embedded capacity resource, up or down, with no downtime (i.e. embedded content is available during the scaling process).

* [uploadapplication.ps1](https://github.com/Azure-Samples/powerbi-powershell/blob/master/uploadapplication.ps1) - Upload local Power BI Application to the specified Workspace

* [Add-User-All-Workspace.ps1](https://github.com/Azure-Samples/powerbi-powershell/blob/master/Add-User-All-Workspace.ps1) - Add specified user to mentioned or all the Workspace

## Prerequisites

To run the scripts in this repo, please install [PowerShell](https://msdn.microsoft.com/en-us/powershell/scripting/setup/installing-windows-powershell), [Azure Resource Manager PowerShell cmdlets](https://www.powershellgallery.com/packages/AzureRM/) and the [Microsoft Power BI Cmdlets](https://docs.microsoft.com/en-us/powershell/power-bi/overview) .

## Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
