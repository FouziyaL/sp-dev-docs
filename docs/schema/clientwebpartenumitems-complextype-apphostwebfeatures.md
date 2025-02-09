---
title: ClientWebPartEnumItems complexType
description: Describes the definition, type, element, and attribute information for ClientWebPartEnumItems complexType.
manager: soliver
ms.date: 06/13/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 34bab690-a8b8-d080-9dbc-2b8fc1a6342f
---

# ClientWebPartEnumItems complexType 

(AppHostWebFeatures)

> [!NOTE] 
> The string `app` appears as part of or all of some element, attribute, and file names because SharePoint Add-ins were originally called "apps for SharePoint." To ensure backward compatibility, the schemas have not been changed.

## Type information

| Information | Location |
|-------------|----------|
| **Namespace** | `http://schemas.microsoft.com/sharepoint/` |
| **Schema File** | apphostwebfeatures.xsd |
| **Extension Base** | None |

## Definition

```XML
    <xs:complexType name="ClientWebPartEnumItems">
        <xs:sequence>
            <xs:element name="EnumItem" type="ClientWebPartEnumItem" minOccurs="0" maxOccurs="unbounded"></xs:element>
        </xs:sequence>
    </xs:complexType>
```

## Elements and attributes

If the schema defines specific requirements, such as **sequence**, **minOccurs**, **maxOccurs**, and **choice**, see the definition section.

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
<td align="left"><p><a href="enumitem-element-clientwebpartenumitems-complextypeapphostwebfeatures.md">EnumItem</a></p></td>
<td align="left"><p><a href="clientwebpartenumitem-complextype-apphostwebfeatures.md">ClientWebPartEnumItem</a></p></td>
<td align="left"><p></p></td>
</tr>
</tbody>
</table>

### Attributes

None.


<br/>

<br/>






