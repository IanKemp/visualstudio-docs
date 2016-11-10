---
title: "Option Strict On disallows operands of type Object for operator &#39;&lt;operatorname&gt;&#39;"
ms.custom: na
ms.date: 10/01/2016
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-csharp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: cd197da8-2676-453b-884b-3231fb6f909d
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
# Option Strict On disallows operands of type Object for operator &#39;&lt;operatorname&gt;&#39;
Option Strict On disallows operands of type Object for operator '<operatorname\>'. Use the Is operator to test for object identity.  
  
 An arithmetic comparison operator such as `=` is used with one or more object variables when `Option Strict` is `On`.  
  
 **Error ID:** BC32013  
  
### To correct this error  
  
1.  Turn `Option Strict Off` if the object variables contain numeric values and you intend an arithmetic comparison.  
  
2.  Use the `Is` operator to compare for object identity.  
  
## See Also  
 [Comparison Operators](../Topic/Comparison%20Operators%20\(Visual%20Basic\).md)   
 [Is Operator](../Topic/Is%20Operator%20\(Visual%20Basic\).md)   
 [Option Strict Statement](../Topic/Option%20Strict%20Statement.md)