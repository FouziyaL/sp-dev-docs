---
title: ElementManifest Element (Feature)
description: Describes the ElementManifest element (Feature) and provides a definition, the elements and attributes, and an example.
manager: soliver
ms.date: 06/14/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 5a6a2865-5d31-45a2-a402-6da6e0f5567a
---

# ElementManifest Element (Feature)

**Applies to**: SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013

Specifies a file that contains a definition for a feature element.

## Definition

```XML
<ElementManifest
  Location = "Text">
</ElementManifest>
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
<td align="left"><p>**Location**</p></td>
<td align="left"><p>Required **Text**. Specifies the relative file path to the root element manifest file, for example, `"controls\searcharea.xml"`.</p></td>
</tr>
</tbody>
</table>

### Child elements

None

### Parent elements

<table>
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><p><a href="elementmanifests-element-feature.md">ElementManifests</a></p></td>
</tr>
</tbody>
</table>

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


## Example

For an example of how this element is used, see [Feature.xml Files](feature-xml-files.md).








