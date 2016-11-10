---
title: "Compiler Error CS0227"
ms.custom: na
ms.date: 10/01/2016
ms.devlang: 
  - CSharp
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-csharp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: b595a1c9-8204-4ff7-a1d0-258b0b1d6ff7
caps.latest.revision: 11
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
# Compiler Error CS0227
Unsafe code may only appear if compiling with /unsafe  
  
 If source code contains the [unsafe](../Topic/unsafe%20\(C%23%20Reference\).md) keyword, then the [/unsafe](../Topic/-unsafe%20\(C%23%20Compiler%20Options\).md) compiler option must also be used. For more information, see [Unsafe Code and Pointers](../Topic/Unsafe%20Code%20and%20Pointers%20\(C%23%20Programming%20Guide\).md).  
  
 To set the unsafe option in Visual Studio 2012, click on **Project** in the main menu, select the **Build** pane, and check the box that says "allow unsafe code."  
  
 The following sample, when compiled without **/unsafe**, will generate CS0227:  
  
```  
// CS0227.cs  
public class MyClass  
{  
   unsafe public static void Main()   // CS0227  
   {  
   }  
}  
```  
  
## See Also  
 [C# Compiler Errors](../Topic/C%23%20Compiler%20Errors.md)