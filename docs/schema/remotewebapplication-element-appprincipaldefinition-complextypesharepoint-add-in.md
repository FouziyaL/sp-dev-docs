---
title: RemoteWebApplication element (AppPrincipalDefinition complexType)
description: Defines the RemoteWebApplication element (AppPrincipalDefinition complexType), which specifies properties of a provider-hosted SharePoint Add-in.
manager: soliver
ms.date: 06/10/2022
ms.audience: Developer
ms.topic: article
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 516ed600-9f2c-10b4-0110-a8237d4da382
---

# RemoteWebApplication element (AppPrincipalDefinition complexType) 

(SharePoint Add-in Manifest)

**Applies to**: SharePoint Add-ins | SharePoint Foundation 2013 | SharePoint Server 2013

Specifies properties of a provider-hosted SharePoint Add-in.

> [!NOTE] 
> The string `app` appears as part of or all of some element, attribute, and file names because SharePoint Add-ins were originally called "apps for SharePoint." To ensure backward compatibility, the schemas have not been changed.

## Element information

|Information|Value|
|---|---|
| **Element type**  | Not defined |
| **Namespace**  | `http://schemas.microsoft.com/sharepoint/2012/app/manifest` |
| **Schema file**  | appmanifest.xsd |

## Definition

```XML 
    <xs:element name="RemoteWebApplication" >
      <xs:attribute name="ClientId" type="AppPermissionAppPrincipalDefinition" use="required"/>
    </xs:element>     
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
<td align="left"><p><a href="appprincipal-element-appdefinition-complextypesharepoint-add-in-manifest.md">AppPrincipal</a></p></td>
<td align="left"><p><a href="appprincipaldefinition-complextype-sharepoint-add-in-manifest.md">AppPrincipalDefinition</a></p></td>
<td align="left"><p>The add-in principal information.</p></td>
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
<col width="20%" />
<col width="20%" />
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
<td align="left"><p>ClientId</p></td>
<td align="left"><p><a href="apppermissionappprincipaldefinition-simpletype-sharepoint-add-in-manifest.md">AppPermissionAppPrincipalDefinition</a></p></td>
<td align="left"><p>required</p></td>
<td align="left"><p>The client id of the add-in principal, a GUID. This should be lowercase.</p></td>
<td align="left"><p>Values of the AppPermissionAppPrincipalDefinition type.</p></td>
</tr>
</tbody>
</table>

<br/>
<br/>






