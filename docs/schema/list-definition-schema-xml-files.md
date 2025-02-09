---
title: List Definition (Schema.xml) Files
description: Outlines the List element in Sharepoint and associated files including a Schema.xml file and a Feature.xml file.
manager: soliver
ms.date: 06/10/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: d46f6a2b-5072-456c-bc94-9c0d20a20e67
---

# List Definition (Schema.xml) Files

**Applies to**: SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013

A list template Feature includes a [Schema.xml](https://msdn.microsoft.com/library/c2f01064-80d8-47ee-b602-ecf4c480ac56(Office.15).aspx) file that serves as the base file for a list definition. 

The [List](list-element-list.md) element is the root element of a Schema.xml file, which contains default view definitions, definitions for special fields used in the list, the toolbar definition for list views, content type declarations, and other metadata for the list.

A list definition includes a [Feature.xml](feature-xml-files.md) file, an element manifest file (see [List Template Files](list-template-files.md)), and a [Schema.xml](https://msdn.microsoft.com/library/c2f01064-80d8-47ee-b602-ecf4c480ac56(Office.15).aspx) file within a Feature folder (%ProgramFiles%\\Common Files\\Microsoft Shared\\web server extensions\\15\\TEMPLATE\\FEATURES). 

For an example that shows how to create a custom list definition, see [How to: Create a Custom List Definition](https://msdn.microsoft.com/library/6f0aed4a-d80a-4e42-8f12-c6b83c8cc207(Office.15).aspx).


## See also

- [List Schema](list-schema.md)








