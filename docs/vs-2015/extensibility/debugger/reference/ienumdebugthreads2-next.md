---
title: "IEnumDebugThreads2::Next | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IEnumDebugThreads2::Next"
helpviewer_keywords: 
  - "IEnumDebugThreads2::Next"
ms.assetid: bcffd954-3c67-4867-96f3-041ddb3e34d4
caps.latest.revision: 10
ms.author: "gregvanl"
manager: "ghogen"
---
# IEnumDebugThreads2::Next
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IEnumDebugThreads2::Next](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/ienumdebugthreads2-next).  
  
Returns the next set of elements from the enumeration.  
  
## Syntax  
  
```cpp#  
HRESULT Next(  
   ULONG           celt,  
   IDebugThread2** rgelt,  
   ULONG*          pceltFetched  
);  
```  
  
```csharp  
int Next(  
   uint            celt,  
   IDebugThread2[] rgelt,  
   ref uint        pceltFetched  
);  
```  
  
#### Parameters  
 `celt`  
 [in] The number of elements to retrieve. Also specifies the maximum size of the `rgelt` array.  
  
 `rgelt`  
 [in, out] Array of [IDebugThread2](../../../extensibility/debugger/reference/idebugthread2.md) elements to be filled in.  
  
 `pceltFetched`  
 [out] Returns the number of elements actually returned in `rgelt`.  
  
## Return Value  
 If successful, returns `S_OK`. Returns `S_FALSE` if fewer than the requested number of elements could be returned; otherwise, returns an error code.  
  
## See Also  
 [IEnumDebugThreads2](../../../extensibility/debugger/reference/ienumdebugthreads2.md)   
 [IDebugThread2](../../../extensibility/debugger/reference/idebugthread2.md)

