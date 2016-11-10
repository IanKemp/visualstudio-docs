---
title: "Properties of Geometry Shapes"
ms.custom: na
ms.date: 10/03/2016
ms.prod: visual-studio-tfs-dev14
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 3993a23e-eab3-4ceb-b475-c395d5992bfc
caps.latest.revision: 21
manager: kamrani
---
# Properties of Geometry Shapes
You can use geometry shapes to specify how instances of domain classes are displayed in a domain-specific language. For more information, see [How to Define a Domain-Specific Language](../VS_IDE/How-to-Define-a-Domain-Specific-Language.md). For more information about how to use these properties, see [Customizing and Extending a Domain-Specific Language](../VS_IDE/Customizing-and-Extending-a-Domain-Specific-Language.md).  
  
 Geometry shapes have the properties that are listed in the following table.  
  
|Property|Description|Default|  
|--------------|-----------------|-------------|  
|Fill Color|The fill color of this shape.|White|  
|Fill Gradient Mode|The fill gradient mode of this shape (Horizontal, Vertical, Forward Diagonal, Backward Diagonal, or None).|Horizontal|  
|Geometry|The geometry of this shape (Rectangle, Rounded Rectangle, Ellipse, or Circle).|Rectangle|  
|Has Default Connection Points|If `True`, the shape will use top, bottom, left, and right connection points in the generated designer.|False|  
|Outline Color|The outline color of this shape.|Black|  
|Outline Dash Style|The outline dash style of this shape (Solid, Dash, Dot, DashDot, DashDotDot, or Custom).|Solid|  
|Outline Thickness|The outline thickness of this shape.|0.03125|  
|Text Color|The color that is used for text decorators that are associated with this shape.|Black|  
|Access Modifier|The access modifier of the class (public or internal).|Public|  
|Custom Attributes|Used to add attributes to the source code class that is generated for this shape.|<none\>|  
|Generates Double Derived|If `True`, both a base class and a partial class (to support customization through overrides) will be generated. For more information, see [Overriding and Extending the Generated Classes](../VS_IDE/Overriding-and-Extending-the-Generated-Classes.md).|False|  
|Has Custom Constructor|If `True`, a custom constructor will be provided in the source code. For more information, see [Overriding and Extending the Generated Classes](../VS_IDE/Overriding-and-Extending-the-Generated-Classes.md).|False|  
|Inheritance Modifier|Describes the kind of inheritance of the source code class that is generated from the shape (`none`, `abstract` or `sealed`).|none|  
|Base Geometry Shape|The base class of this shape.|(none)|  
|Name|The name of this shape.|Current name|  
|Namespace|The namespace that is affiliated with this shape.|Current namespace|  
|Tooltip Type|How the tooltip is defined (fixed, variable, or none). If fixed, then the value of the `Fixed Tooltip Text` property is used as the tooltip; if variable, then the tooltip is defined in custom code.|None|  
|Notes|Informal notes that are associated with this element.|<none\>|  
|Initial Height|Initial height of this shape, in inches.|1|  
|Initial Width|Initial width of this shape, in inches.|1.5|  
|Exposed Fill Color As Property<br /><br /> Exposed Fill Gradient Mode<br /><br /> Exposed Outline Color As Property<br /><br /> Exposed Outline Dash Style As Property<br /><br /> Exposed Outline Thickness As Property<br /><br /> Exposes Text Color|If `True`, the user can set the stated property of a shape. To set this, right-click the shape definition and click **Add Exposed**.|False|  
|Description|The description that is used to document the generated designer.|<none\>|  
|Display Name|The name that will be displayed in the generated designer for this shape.|<none\>|  
|Fixed Tooltip Text|The text that is used for a fixed tooltip.|<none\>|  
|Help Keyword|The keyword that is used to index F1 help for this shape.|<none\>|  
  
## See Also  
 [Domain-Specific Language Tools Glossary](assetId:///ca5e84cb-a315-465c-be24-76aa3df276aa)