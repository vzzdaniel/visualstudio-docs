---
title: "How to: Edit XML Files | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-general"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 07fa3ecf-6345-4d30-9d85-d5ef5b083319
caps.latest.revision: 2
author: "gewarren"
ms.author: "gewarren"
manager: "ghogen"
---
# How to: Edit XML Files
The XML Editor is the new editor for XML files. It can be used on a stand-alone XML file, or on a file associated with a Visual Studio project. The XML Editor is associated with the following file extensions: .config, .dtd, .xml, .xsd, .xdr, .xsl, .xslt, and .vssettings. The XML Editor is also associated with any other file type that has no specific editor registered, and that contains XML or DTD content.  
  
> [!NOTE]
>  XHTML documents are handled by the HTML Editor.  
  
### To edit an XML file  
  
1.  Double-click the file you want to edit.  
  
### To add a new XML file to a project  
  
1.  From the **Project** menu, select **Add New Item**.  
  
2.  Select **XML File** from the **Templates** pane.  
  
3.  Enter the filename in the **Name** field and press **Add**.  
  
     The XML file is added to the project and opened in the XML Editor. The file contains the default XML declaration, `<?xml version="1.0" encoding="utf-8" ?>`.  
  
### To add an existing XML file to a project  
  
1.  From the **Project** menu, select **Add Existing Item**.  
  
     The **Add Existing Item** dialog box appears.  
  
2.  Select an XML file and press **Add**.  
  
### To create a new XML or XSLT file  
  
1.  From the **File** menu, select **New**.  
  
     The **New File** dialog box appears.  
  
2.  Select **XML File** to create a new XML file; or, select **XSLT File** to create a new XSLT style sheet.  
  
3.  Click **Open**.  
  
### To create a project for XML files  
  
1.  From the **File** menu, select **New**, and then select **Project**.  
  
     The **New Project** dialog box appears.  
  
2.  Select the code language of your choice, select **Empty Project**, and click **OK**.  
  
3.  Add XML files to the project.  
  
     The XML Editor finds the schemas you add to this project and uses them for validation and IntelliSense in any XML, schema, or XSLT files that you edit while this project is open.  
  
## See Also  
 [XML Editor](../xml-tools/xml-editor.md)   
 [XML Document Properties, Properties Window](../xml-tools/xml-document-properties-properties-window.md)   
 [How to: Create an XML Schema from an XML Document](../xml-tools/how-to-create-an-xml-schema-from-an-xml-document.md)