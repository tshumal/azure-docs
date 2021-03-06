---
title: Create your first Azure Function | Microsoft Docs
description: Build your first Azure Function, a serverless application, in less than two minutes.
services: functions
documentationcenter: na
author: ggailey777
manager: erikre
editor: ''
tags: ''

ms.assetid: 4a1669e7-233e-4ea2-9b83-b8624f2dbe59
ms.service: functions
ms.devlang: multiple
ms.topic: hero-article
ms.tgt_pltfrm: multiple
ms.workload: na
ms.date: 03/14/2016
ms.author: glenga

---
# Create your first Azure Function

This topic shows you how to use the Azure Functions quickstart in the portal to create a simple "hello world"  function that is invoked by an HTTP request. To learn more about Azure Functions, see the [Azure Functions Overview](functions-overview.md).

Before you start, you must have an Azure account. [Free accounts](https://azure.microsoft.com/free/) are available. You can also [try Azure Functions](https://azure.microsoft.com/try/app-service/functions/) without having to register with Azure.

## Create a function from the portal quickstart

1. Go to the [Azure Functions portal](https://functions.azure.com/signin) and sign in with your Azure account. 
 
2. Type a unique **Name** for your new function app or accept the autogenerated one, select your preferred **Region**, then click **Create + get started**. A valid name can contain only letters, numbers, and hyphens. Underscore (**_**) is not an allowed character.

3. In the **Quickstart** tab, click **WebHook + API** and choose a language for your function, then click **Create a function**. A new predefined function is created in your chosen language. 
   
    ![](./media/functions-create-first-azure-function/function-app-quickstart-node-webhook.png)

4. (Optional) At this point in the quickstart, you can choose to take a quick tour of Azure Functions features in the portal. After you have completed or skipped the tour, you can test your new function by sending an HTTP request.

## Test the function
[!INCLUDE [Functions quickstart test](../../includes/functions-quickstart-test.md)]

## Watch the video
The following video shows how to perform the basic steps in this tutorial. 

> [!VIDEO https://channel9.msdn.com/Series/Windows-Azure-Web-Sites-Tutorials/Create-your-first-Azure-Function-simple/player]
> 


## Next steps
[!INCLUDE [Functions quickstart next steps](../../includes/functions-quickstart-next-steps.md)]

[!INCLUDE [Getting Started Note](../../includes/functions-get-help.md)]

