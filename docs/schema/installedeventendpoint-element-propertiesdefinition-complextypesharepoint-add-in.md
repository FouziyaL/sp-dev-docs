---
title: InstalledEventEndpoint element (PropertiesDefinition complexType)
description: InstalledEventEndpoint element (PropertiesDefinition complexType) is the URL of the installed event receiver endpoint.
manager: soliver
ms.date: 06/10/2022
ms.audience: Developer
ms.topic: article
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: af9f83d8-8325-3ede-d7b0-bb82c0445eb9
---

# InstalledEventEndpoint element (PropertiesDefinition complexType) 

(SharePoint Add-in Manifest)

**Applies to**: SharePoint Add-ins | SharePoint Foundation 2013 | SharePoint Server 2013

The Url of the installed event receiver endpoint.

> [!NOTE] 
> The string `app` appears as part of or all of some element, attribute, and file names because SharePoint Add-ins were originally called "apps for SharePoint." To ensure backward compatibility, the schemas have not been changed.

## Element information

| Information  | location  |
|---|---|
| **Element type**  | UrlElementDefinitions |
| **Namespace**  | `http://schemas.microsoft.com/sharepoint/2012/app/manifest` |
| **Schema file**  | appmanifest.xsd |

## Definition

```XML
   <xs:element name="InstalledEventEndpoint"  type="UrlElementDefinition"
        minOccurs="0"
        maxOccurs="1"
        >
   </xs:element>
```        

## Elements and attributes

If the schema defines specific requirements, such as **sequence**, **minOccurs**, **maxOccurs**, and **choice**, see the definition section.

### Parent elements

<table>
<colgroup>
<col width="30%" />
<col width="30%" />
<col width="40%" />
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
<td align="left"><p><a href="properties-element-appdefinition-complextypesharepoint-add-in-manifest.md">Properties</a></p></td>
<td align="left"><p><a href="propertiesdefinition-complextype-sharepoint-add-in-manifest.md">PropertiesDefinition</a></p></td>
<td align="left"><p>Contains information that is global to the add-in.</p></td>
</tr>
</tbody>
</table>

<br/>

### Child elements

None.

<br/>

### Attributes

None.

<br/>
<br/>





