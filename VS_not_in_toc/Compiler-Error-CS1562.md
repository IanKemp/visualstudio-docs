---
title: "Compiler Error CS1562"
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
ms.assetid: fbadbcc6-9cf2-4af6-b372-fd4e4da4402e
caps.latest.revision: 7
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
# Compiler Error CS1562
Outputs without source must have the /out option specified  
  
 The compilation could create an output file, but there was no source code file as input from which the name of the output file could be implied. For example, you may be trying to compile a metadata- or resource-only file.  
  
 Use the [/out](../Topic/-out%20\(C%23%20Compiler%20Options\).md) compiler option to specify the name of the output file.