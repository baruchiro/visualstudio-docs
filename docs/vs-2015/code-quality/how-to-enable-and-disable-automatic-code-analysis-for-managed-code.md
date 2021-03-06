---
title: "How to: Enable and Disable Automatic Code Analysis for Managed Code | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-devops-test"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 7c22d194-5fea-4f23-b02d-19344fa64a64
caps.latest.revision: 10
author: gewarren
ms.author: gewarren
manager: "wpickett"
---
# How to: Enable and Disable Automatic Code Analysis for Managed Code
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

The latest version of this topic can be found at [How to: Enable and Disable Automatic Code Analysis for Managed Code](https://docs.microsoft.com/visualstudio/code-quality/how-to-enable-and-disable-automatic-code-analysis-for-managed-code).  
  
You can configure Code Analysis to run before each build of a managed code project. You can set different Code Analysis properties for each [!INCLUDE[vs_current_short](../includes/vs-current-short-md.md)] configuration.  
  
### To enable or disable automatic code analysis  
  
1.  In **Solution Explorer**, right-click the project, and then click **Properties**.  
  
2.  In the properties dialog box for the project, click **Code Analysis**.  
  
3.  Specify the build type in **Configuration** and the target platform in **Platform**.  
  
4.  To enable or disable automatic code analysis, select or clear the **Enable Code Analysis on Build (defines CODE_ANALYSIS constant)** check box.



