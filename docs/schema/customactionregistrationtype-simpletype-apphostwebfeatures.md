---
title: CustomActionRegistrationType simpleType
description: Outlines information, a definition, and enumeration values for the CustomActionRegistrationType simpleType in Sharepoint.
manager: soliver
ms.date: 06/09/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: bee593c6-802f-8d0c-d619-4adbcc6b1aae
---

# CustomActionRegistrationType simpleType 

(AppHostWebFeatures)

> [!NOTE] 
> The string `app` appears as part of or all of some element, attribute, and file names because SharePoint Add-ins were originally called "apps for SharePoint." To ensure backward compatibility, the schemas have not been changed.

## Type information
| Name  | Value  |
|---|---|
| **Base Type**  | xs:string |
| **Namespace**  | `http://schemas.microsoft.com/sharepoint/` |
| **Schema file**  | apphostwebfeatures.xsd |

## Definition

```XML
    <xs:simpleType name="CustomActionRegistrationType">
        <xs:restriction base="xs:string">
            <xs:enumeration value="List" />
            <xs:enumeration value="ContentType" />
            <xs:enumeration value="FileType" />
            <xs:enumeration value="ProgId" />
        </xs:restriction>
    </xs:simpleType>
```

## Enumeration values

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><p>Value</p></th>
<th align="left"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>List</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p>ContentType</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p>FileType</p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p>ProgId</p></td>
<td align="left"><p></p></td>
</tr>
</tbody>
</table>

<br/>

<br/>







