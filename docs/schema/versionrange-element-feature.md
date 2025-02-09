---
title: VersionRange Element (Feature)
manager: soliver
ms.date: 06/14/2022
description: Describes VersionRange Element (Feature) and provides information on elements and attributes.
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: cd715e38-6ec3-43b2-8007-6d0ed8865d91
---

# VersionRange Element (Feature)

**Applies to**: SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013

Specifies a range of previous versions of the Feature to which the upgrade actions should apply.

## Definition

```XML
<VersionRange 
  BeginVersion = string
  EndVersion = string>
  <AddContentTypeField />
  <ApplyElementManifests> ... </ApplyElementManifests>
  <CustomUpgradeActions> ... </CustomUpgradeActions>
  <MapFile />
</VersionRange>
```

## Elements and attributes

The following sections describe attributes, child elements, and parent elements.

### Attributes

> [!TIP] 
> The **BeginVersion** and **EndVersion** attributes set the range of previous versions of the Feature to which the child upgrade elements are applied. The **BeginVersion** value is *inclusive*, but the **EndVersion** attribute is *exclusive*.

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
<td align="left"><p>**BeginVersion**</p></td>
<td align="left"><p>Optional **string**. Specifies the earliest version number to which the child upgrade elements will apply, in the format *n.n.n.n*, where each *n* can be up to four digits. If this attribute is not used, the beginning of the range is effectively 0.0.0.0; that is, every previous version of the Feature will be considered within the lower bound of the range.</p></td>
</tr>
<tr class="even">
<td align="left"><p>**EndVersion**</p></td>
<td align="left"><p>Optional **string**. Specifies the *earliest* version number to which the upgrade will *not* apply. The format is *n.n.n.n*, where each *n* can be up to four digits. If this attribute is not used, every previous version of the Feature will be considered within the upper bound of the range.</p></td>
</tr>
</tbody>
</table>

### Child elements

|  Child Elements  |
| --- |
| [AddContentTypeField Element (Feature)](addcontenttypefield-element-feature.md) |
| [ApplyElementManifests Element (Feature)](applyelementmanifests-element-feature.md) |
| [CustomUpgradeAction Element (Feature)](customupgradeaction-element-feature.md) |
| [MapFile Element (Feature)](mapfile-element-feature.md) |

### Parent elements

[UpgradeActions Element (Feature)](upgradeactions-element-feature.md)

### Occurrences

<table>
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><p>Minimum: 0</p>
<p>Maximum: Unbounded</p></td>
</tr>
</tbody>
</table>








