---
title: "ButtonText Element | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "ButtonText element (VSCT XML schema)"
  - "VSCT XML schema elements, ButtonText"
ms.assetid: 56aba884-0356-4894-ae4e-32d3938f6865
caps.latest.revision: 6
ms.author: "gregvanl"
manager: "ghogen"
---
# ButtonText Element
This field lets you specify the text that appears in various menus. By default, the `ButtonText` element appears in menu controllers. The `ButtonText` element also becomes the default if the other text fields are blank. The `ButtonText` element cannot be blank even if the other text fields are specified.  
  
## Syntax  
  
```  
<ButtonText>My Command</ButtonText>  
```  
  
## Attributes and Elements  
 The following sections describe attributes, child elements, and parent elements.  
  
### Attributes  
 None.  
  
### Child Elements  
 None.  
  
### Parent Elements  
  
|Element|Description|  
|-------------|-----------------|  
|[Strings Element](../extensibility/strings-element.md)|Groups text elements, such as `ButtonText` and `CommandName`.|  
  
## Text Value  
 The text value of the `ButtonText` element provides the text that is displayed for menu items, combos, and other user interface (UI) elements that have visible text.  
  
## See Also  
 [Visual Studio Command Table (.Vsct) Files](../extensibility/internals/visual-studio-command-table-dot-vsct-files.md)