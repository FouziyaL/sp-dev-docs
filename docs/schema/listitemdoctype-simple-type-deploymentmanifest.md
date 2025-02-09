---
title: "ListItemDocType Simple Type (DeploymentManifest)"
description: Outlines a definition and enumeration values for the ListItemDocType Simple Type (DeploymentManifest) in Sharepoint.
manager: soliver
ms.date: 06/10/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 1174a051-a3f0-4e24-9e2f-758a6186b67b
---

# ListItemDocType Simple Type (DeploymentManifest)

**Applies to:** SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013 
  
Specifies the document type of a specified list item.

## Definition

```XML
<xs:simpleType name="ListItemDocType">
   <xs:restriction base="xs:string">
      <xs:enumeration value="File" />
      <xs:enumeration value="Folder" />
      <xs:enumeration value="Unknown" />
   </xs:restriction>
</xs:simpleType>

```

## Enumeration values

|**Value**|**Description**|
|:-----|:-----|
|**File** <br/> |Specifies a list item object of type file.  <br/> |
|**Folder** <br/> |Specifies a list item object of type folder.  <br/> |
|**Unknown** <br/> |Indicates that a list item object is of unknown type.  <br/> |
   
### Remarks

Objects of type **Unknown** are typically Web object types. This enumeration provides values for the **DocType** attribute on the [ListItem Element (DeploymentManifest - SPGenericObject)](listitem-element-deploymentmanifestspgenericobject.md).
  
## See also

- [DeploymentManifest Schema](deploymentmanifest-schema.md)
- [ListItem Element (DeploymentManifest - SPGenericObject)](listitem-element-deploymentmanifestspgenericobject.md)

