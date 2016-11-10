---
title: "&#39;Select Case&#39; must end with a matching &#39;End Select&#39;"
ms.custom: na
ms.date: 10/01/2016
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-csharp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: f0809aa5-e6c9-43c9-9664-4ff02825c3d8
caps.latest.revision: 8
manager: douge
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
# &#39;Select Case&#39; must end with a matching &#39;End Select&#39;
A `Select` or `Select Case` statement occurs without a corresponding `End Select` statement. An `End Select` statement must be used to end the `Select` block.  
  
 **Error ID:** BC30095  
  
### To correct this error  
  
1.  If this `Select` block is part of a set of nested `Select` blocks, make sure each block is properly terminated.  
  
2.  Add an `End Select` statement to the end of the `Select` block.  
  
## See Also  
 [Select...Case Statement](../Topic/Select...Case%20Statement%20\(Visual%20Basic\).md)