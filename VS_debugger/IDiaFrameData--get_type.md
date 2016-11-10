---
title: "IDiaFrameData::get_type"
ms.custom: na
ms.date: 10/03/2016
ms.devlang: 
  - C++
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - vs-ide-debug
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: efca38b5-c479-4d0a-a164-f903f25c5509
caps.latest.revision: 8
manager: ghogen
translation.priority.ht: 
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - ru-ru
  - zh-cn
  - zh-tw
translation.priority.mt: 
  - cs-cz
  - pl-pl
  - pt-br
  - tr-tr
---
# IDiaFrameData::get_type
Retrieves the compiler-specific frame type.  
  
## Syntax  
  
```cpp#  
HRESULT get_type (   
   DWORD* pRetVal  
);  
```  
  
#### Parameters  
 `pRetVal`  
 [out] Returns a value from the [StackFrameTypeEnum Enumeration](../VS_debugger/StackFrameTypeEnum.md) enumeration that indicates the compiler-specific frame type.  
  
## Return Value  
 If successful, returns `S_OK`. Returns `S_FALSE` if this property is not supported. Otherwise, returns an error code.  
  
## See Also  
 [IDiaFrameData](../VS_debugger/IDiaFrameData.md)   
 [StackFrameTypeEnum Enumeration](../VS_debugger/StackFrameTypeEnum.md)