---
title: Validate the Azure VNET to use with Azure RemoteApp | Microsoft Docs
description: Learn how to make sure your Azure VNET is ready to use with Azure RemoteApp
services: remoteapp
documentationcenter: ''
author: msmbaldwin
manager: mbaldwin

ms.assetid: b573ba02-4587-4be5-9821-27bd891a73b2
ms.service: remoteapp
ms.workload: compute
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.date: 11/23/2016
ms.author: mbaldwin

---
# Validate the Azure VNET to use with Azure RemoteApp
> [!IMPORTANT]
> Azure RemoteApp is being discontinued. Read the [announcement](https://go.microsoft.com/fwlink/?linkid=821148) for details.
> 
> 

Before you use an Azure VNET with Azure RemoteApp, you might want to validate the VNET. This helps prevent issues with connectivity.

To validate your Azure VNET, do the following:

1. Create an Azure virtual machine inside the subnet of the Azure VNET you want to use with Azure RemoteApp.
2. Connect to that VM by using the **Connect** option in the management portal.
3. Join the virtual machine to the same domain that you want to use with Azure RemoteApp. If you are creating a hybrid collection that connects to your on-premises network, join the virtual machine to your local domain.

If this is successful, the Azure VNET is ready to use with RemoteApp.

For more information about the end-to-end hybrid collection workflow, see the following articles:

* [How to plan your virtual network for Azure RemoteApp](remoteapp-planvnet.md)
* [Create a hybrid collection](remoteapp-create-hybrid-deployment.md)
* [Deploy Azure RemoteApp collection to your Azure Virtual Network (with support for ExpressRoute)](http://blogs.msdn.com/b/rds/archive/2015/04/23/deploy-azure-remoteapp-collection-to-your-azure-virtual-network-with-support-for-expressroute.aspx)

