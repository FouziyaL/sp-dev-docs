---
title: "SPDeploymentObjectType Simple Type (DeploymentExportSettings)"
manager: soliver
ms.date: 06/13/2022
description: Describes SPDeploymentObjectType Simple Type (DeploymentExportSettings) and includes information on elements and attributes.
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 1e83dd6b-2946-45d7-8bd3-29c8e6ad6ddd
---

# SPDeploymentObjectType Simple Type (DeploymentExportSettings)

**Applies to:** SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013
  
Provides values for the **Type** attribute on the [DeploymentObject Element (DeploymentExportSettings)](deploymentobject-element-deploymentexportsettings.md). 

## Definition

```XML
<xs:simpleType name="SPDeploymentObjectType">
        <xs:restriction base="xs:string">
                <xs:enumeration value="Site" />
                <xs:enumeration value="Web" /> 
                <xs:enumeration value="Folder" />
                <xs:enumeration value="List" /> 
                <xs:enumeration value="ListItem" />
                <xs:enumeration value="File" />
        </xs:restriction>
</xs:simpleType>

```

## Enumeration values

|**Value**|**Description**|
|:-----|:-----|
|**Site** <br/> |Specifies a site (**SPSite**) object type.  <br/> |
|**Web** <br/> |Specifies a Web (**SPWeb**) object type.  <br/> |
|**Folder** <br/> |Specifies a folder (**SPFolder**) object type.  <br/> |
|**List** <br/> |Specifies a list or document library (**SPList**) object type.  <br/> |
|**ListItem** <br/> |Specifies a list item (**SPListItem**) object type.  <br/> |
|**File** <br/> |Specifies a file (**SPFile**) object type.  <br/> |
   
### Remarks

The **SPDeploymentObjectType** simple type values specify the object type for Windows SharePoint Services 3.0 top-level objects marked for export to the content migration package. 
  
## See also

- [DeploymentExportSettings Schema](deploymentexportsettings-schema.md)
- [DeploymentObject Element (DeploymentExportSettings)](deploymentobject-element-deploymentexportsettings.md)

