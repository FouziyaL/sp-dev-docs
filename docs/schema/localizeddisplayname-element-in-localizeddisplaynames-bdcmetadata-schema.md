---
title: LocalizedDisplayName Element in LocalizedDisplayNames (BDCMetadata Schema)
description: Details on the LocalizedDisplayName Element in LocalizedDisplayNames (BDCMetadata Schema)
manager: soliver
ms.date: 06/10/2022
ms.audience: Developer
ms.topic: reference
f1_keywords:
- VS.SharePointTools.BDC.LocalizedDisplayName
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 93fb80ef-6347-b463-da90-4980d872678e
---

# LocalizedDisplayName Element in LocalizedDisplayNames (BDCMetadata Schema)

**Applies to**: SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013

Specifies a localized name.

**Namespace**: `http://schemas.microsoft.com/windows/2007/BusinessDataCatalog`

**Schema**: BDCMetadata

```XML<
<LocalizedDisplayName LCID = "Integer"> </LocalizedDisplayName>
```

## Elements and attributes

The following sections describe attributes, child elements, and parent elements.

### Attributes

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><p>Attribute</p></th>
<th align="left"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>**LCID**</p></td>
<td align="left"><p>Required.</p>
<p>The language code identifier (LCID).</p>
<p>Attribute type: **Integer**</p></td>
</tr>
</tbody>
</table>

### Child elements

None.

### Parent elements

  
| Element | Description |
| --- | --- |
| [LocalizedDisplayNames Element in MetadataObject (BDCMetadata Schema)](localizeddisplaynames-element-in-metadataobject-bdcmetadata-schema.md) | The **LocalizedDisplayNames** element that contains this **LocalizedDisplayName**. |








