---
title: ElementManifests element (FeatureDefinition complexType)
description: Describes the ElementManifests element (FeatureDefinition complexType) and provides the element information, a definition, and the elements and attributes.
manager: soliver
ms.date: 06/14/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 5f720156-326c-d29e-a8f6-5ba12842ce0e
---

# ElementManifests element (FeatureDefinition complexType) 

(AppHostWebFeatures)

> [!NOTE] 
> The string `app` appears as part of or all of some element, attribute, and file names because SharePoint Add-ins were originally called "apps for SharePoint." To ensure backward compatibility, the schemas have not been changed. 

## Element information

| Information | Location |
|---|---|
| **Element type**  | ElementManifestReferences |
| **Namespace**  | `http://schemas.microsoft.com/sharepoint/` |
| **Schema file**  | apphostwebfeatures.xsd |

## Definition

```XML
    <xs:element name="ElementManifests" type="ElementManifestReferences" minOccurs="0" maxOccurs="1"></xs:element>
```

## Elements and attributes 

If the schema defines specific requirements, such as **sequence**, **minOccurs**, **maxOccurs**, and **choice**, see the definition section.
 

### Parent elements

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
<td align="left"><p><a href="feature-element-apphostwebfeatures.md">Feature</a></p></td>
<td align="left"><p><a href="featuredefinition-complextype-apphostwebfeatures.md">FeatureDefinition</a></p></td>
<td align="left"><p></p></td>
</tr>
</tbody>
</table>

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







