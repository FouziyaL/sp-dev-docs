---
title: SourceEntity Element in Association
description: SourceEntity Element in Association specifies a source external content type of an Association.
manager: soliver
ms.date: 06/14/2022
ms.audience: Developer
ms.topic: reference
f1_keywords:
- VS.SharePointTools.BDC.SourceEntity
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 19fb5f38-4e85-7fb0-2562-281b9a9ffbef
---

# SourceEntity Element in Association 

(BDCMetadata Schema)

**Applies to**: SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013

Specifies a source external content type of an **Association**.

**Namespace**: `http://schemas.microsoft.com/windows/2007/BusinessDataCatalog`

**Schema**: BDCMetadata

```XML
<SourceEntity Namespace = "String" Name = "String"> </SourceEntity>
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
<td align="left"><p>**Namespace**</p></td>
<td align="left"><p>Required.</p>
<p>The namespace of the external content type that is the source of the **Association** that contains this element.</p>
<p>Attribute type: **String**</p></td>
</tr>
<tr class="even">
<td align="left"><p>**Name**</p></td>
<td align="left"><p>Required.</p>
<p>The name of the external content type that is the source of the **Association** that contains this element.</p>
<p>Attribute type: **String**</p></td>
</tr>
</tbody>
</table>

### Child elements

None.

### Parent elements

| Element | Description |
| --- | --- |
| [Association Element in MethodInstances (BDCMetadata Schema)](association-element-in-methodinstances-bdcmetadata-schema.md) | The **Association** that contains this element. |








