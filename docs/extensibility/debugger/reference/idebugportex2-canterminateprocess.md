---
title: "IDebugPortEx2::CanTerminateProcess | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: 
  - "vs-ide-sdk"
ms.topic: "conceptual"
f1_keywords: 
  - "IDebugPortEx2::CanTerminateProcess"
helpviewer_keywords: 
  - "IDebugPortEx2::CanTerminateProcess"
ms.assetid: 111f65d8-5a1a-42b3-9de3-dd9bb03a33fd
author: "gregvanl"
ms.author: "gregvanl"
manager: douge
ms.workload: 
  - "vssdk"
---
# IDebugPortEx2::CanTerminateProcess
Determines whether a process can be terminated.  
  
## Syntax  
  
```cpp  
HRESULT CanTerminateProcess(   
   IDebugProcess2* pPortProcess  
);  
```  
  
```csharp  
HRESULT CanTerminateProcess(   
   IDebugProcess2 pPortProcess  
);  
```  
  
#### Parameters  
 `pPortProcess`  
 [in] An [IDebugProcess2](../../../extensibility/debugger/reference/idebugprocess2.md) object representing the process to be terminated.  
  
## Return Value  
 Returns `S_OK` if the process can be terminated; otherwise, returns `S_FALSE`.  
  
## See Also  
 [IDebugPortEx2](../../../extensibility/debugger/reference/idebugportex2.md)   
 [IDebugProcess2](../../../extensibility/debugger/reference/idebugprocess2.md)