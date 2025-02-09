---
title: CustomProperty Element in ArrayOfCustomProperty
description: Outlines attributes, child elements, and parent elements for the CustomProperty element in Sharepoint.
manager: soliver
ms.date: 06/09/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: bb2e9d1e-ed98-a45b-1614-cef13aa6c18c
---

# CustomProperty Element in ArrayOfCustomProperty 

(LayoutDefinitions Schema)

**Applies to**: SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013

Defines a custom property of a Container or an Office External Part.

**Namespace**: `http://schemas.microsoft.com/office/2009/05/BusinessApplications/Layout`

**Schema**: LayoutDefinitions

```XML
<CustomProperty Name = "String" Value = "String"> </CustomProperty>
```

## Elements and attributes

The following sections describe attributes, child elements, and parent elements.

### Attributes

<table>
<colgroup>
<col width="20%" />
<col width="80%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><p>Attribute</p></th>
<th align="left"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>**Name**</p></td>
<td align="left"><p>Required.</p>
<p>The name of the property.</p>
<p>Attribute type: **String**</p></td>
</tr>
<tr class="even">
<td align="left"><p>**Value**</p></td>
<td align="left"><p>Required.</p>
<p>The value of the property.</p>
<p>Attribute type: **String**</p></td>
</tr>
</tbody>
</table>

### Child elements

None.

### Parent elements

|Element|Description|
|----------|-----------|
|[CustomProperties Element in UIElement (LayoutDefinitions Schema)](customproperties-element-in-uielement-layoutdefinitions-schema.md)|The list of custom properties that contains this custom property. |







