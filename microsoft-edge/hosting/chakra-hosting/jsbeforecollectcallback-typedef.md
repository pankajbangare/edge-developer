---
description: "A callback called before collection."
title: "JsBeforeCollectCallback Typedef | Microsoft Docs"
ms.custom: ""
ms.date: "01/18/2017"
ms.prod: "windows-client-threshold"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "reference"
ms.assetid: 58bece47-4e6d-49e7-a93d-b6a8f9928b41
caps.latest.revision: 6
author: "erikadoyle"
ms.author: "edoyle"
manager: "jken"
---
# JsBeforeCollectCallback Typedef
A callback called before collection.  
  
## Syntax  
  
```cpp  
typedef void (CALLBACK *JsBeforeCollectCallback)(  
_In_opt_ void *callbackState  
);  
```  
  
#### Parameters  
 callbackState  
 The state passed to JsSetBeforeCollectCallback.  
  
## Remarks  
 Use JsSetBeforeCollectCallback to register this callback.  
  
## Requirements  
 **Header:** jsrt.h  
  
## See Also  
 [Reference (JavaScript Runtime)](../chakra-hosting/reference-javascript-runtime.md)