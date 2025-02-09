---
title: ApplyElementManifests element (UpgradeActionsGroup group)
description: Describes the ApplyElementManifests element (UpgradeActionsGroup group) schema and provides the schema's definition and child elements.
manager: soliver
ms.date: 06/14/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 060aa8d2-a12a-ff26-2ca4-ebf9b6dc88f1
---

# ApplyElementManifests element (UpgradeActionsGroup group) 

(AppHostWebFeatures)

> [!NOTE] 
> The string `app` appears as part of or all of some element, attribute, and file names because SharePoint Add-ins were originally called "apps for SharePoint." To ensure backward compatibility, the schemas have not been changed. 

## Element information

|Information|Location|
|---|---|
| **Element type**  | ElementManifestReferences |
| **Namespace**  | `http://schemas.microsoft.com/sharepoint/` |
| **Schema file**  | apphostwebfeatures.xsd |

## Definition

```XML
    <xs:element name="ApplyElementManifests" type="ElementManifestReferences" minOccurs="0" maxOccurs="unbounded"></xs:element>
```

## Elements and attributes

If the schema defines specific requirements, such as **sequence**, **minOccurs**, **maxOccurs**, and **choice**, see the definition section.


### Parent elements

None.

<br/>

### Child elements

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><p>Element</p></th>
<th align="left"><p>Type</p></th>
<th align="left"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p><a href="elementfile-element-elementmanifestreferences-complextypeapphostwebfeatures.md">ElementFile</a></p></td>
<td align="left"><p><a href="elementmanifestreference-complextype-apphostwebfeatures.md">ElementManifestReference</a></p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p><a href="elementmanifest-element-elementmanifestreferences-complextypeapphostwebfeatures.md">ElementManifest</a></p></td>
<td align="left"><p><a href="elementmanifestreference-complextype-apphostwebfeatures.md">ElementManifestReference</a></p></td>
<td align="left"><p></p></td>
</tr>
</tbody>
</table>

<br/>

### Attributes

None.

<br/> 
<br/> 






