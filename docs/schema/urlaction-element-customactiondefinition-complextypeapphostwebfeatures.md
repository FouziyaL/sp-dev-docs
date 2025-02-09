---
title: UrlAction element (CustomActionDefinition complexType)
description: Describes the definition, element, and attribute information for the UrlAction element (CustomActionDefinition complexType).
manager: soliver
ms.date: 06/14/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 467fb784-088c-1cef-425f-ea1d94836c45
---

# UrlAction element (CustomActionDefinition complexType) 

(AppHostWebFeatures)

> [!NOTE] 
> The string `app` appears as part of or all of some element, attribute, and file names because SharePoint Add-ins were originally called "apps for SharePoint." To ensure backward compatibility, the schemas have not been changed. 

## Element information

| Information | Location |
|---|---|
| **Element type**  | UrlActionDefinition |
| **Namespace**  | `http://schemas.microsoft.com/sharepoint/` |
| **Schema file**  | apphostwebfeatures.xsd |

## Definition

```XML
    <xs:element name="UrlAction" type="UrlActionDefinition" minOccurs="0" maxOccurs="1"></xs:element>
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
<td align="left"><p><a href="customaction-element-elementdefinitioncollection-complextypeapphostwebfeatures.md">CustomAction</a></p></td>
<td align="left"><p><a href="customactiondefinition-complextype-apphostwebfeatures.md">CustomActionDefinition</a></p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p><a href="customaction-element-customactiondefinitions-complextypeapphostwebfeatures.md">CustomAction</a></p></td>
<td align="left"><p><a href="customactiondefinition-complextype-apphostwebfeatures.md">CustomActionDefinition</a></p></td>
<td align="left"><p></p></td>
</tr>
</tbody>
</table>

<br/> 

### Child elements

None.

<br/> 

### Attributes

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="10%" />
<col width="30%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><p>Attribute</p></th>
<th align="left"><p>Type</p></th>
<th align="left"><p>Required</p></th>
<th align="left"><p>Description</p></th>
<th align="left"><p>Possible values</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>Url</p></td>
<td align="left"><p>AbsoluteOrRelativeUrl</p></td>
<td align="left"><p>required</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the AbsoluteOrRelativeUrl type.</p></td>
</tr>
</tbody>
</table>

<br/> 

<br/> 








