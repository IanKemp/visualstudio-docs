---
title: "Compiler Error CS0737"
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
ms.assetid: d2247770-5546-46f2-a01d-8e2ebfcbb859
caps.latest.revision: 9
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
# Compiler Error CS0737
'type name' does not implement interface member 'member name'. 'method name' cannot implement an interface member because it is not public.  
  
 A method that implements an interface member must have public accessibility. All interface members are `public`.  
  
### To correct this error  
  
1.  Add the [public](../Topic/public%20\(C%23%20Reference\).md) access modifier to the method.  
  
## Example  
 The following code generates CS0737:  
  
```  
// cs0737.cs  
interface ITest  
{  
    // Default access of private with no modifier.  
    int Return42();  
    // Try the following line instead.  
    // public int Return42();  
}  
  
struct Struct1 : ITest // CS0737  
{  
    int Return42() { return (42); }  
}  
  
public class Test  
{  
    public static int Main(string[] args)  
    {  
        Struct1 s1 = new Struct1();  
  
        return (1);  
    }  
  
}  
```  
  
## See Also  
 [Interfaces](../Topic/Interfaces%20\(C%23%20Programming%20Guide\).md)