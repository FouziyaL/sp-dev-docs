---
title: "ManifestFile element (DeploymentSystemData)"
description: Outlines a definition, type, attributes, child elements, and parent elements for the ManifestFile element in Sharepoint.
manager: soliver
ms.date: 06/09/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 37164e6f-d94d-451c-80c1-5558bd4889ca
---

# ManifestFile element (DeploymentSystemData)

**Applies to:** SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013
  
Represents a system data file (SystemData.xml) exported to the content migration package.

## Definition

```XML
DECLARATION
<xs:element 
    name="ManifestFile" 
    type="SPManifestFile" 
    minOccurs="1" maxOccurs="unbounded" 
/>
USAGE
<ManifestFiles>
    <ManifestFile
        Name="xs:string"
    />
</ManifestFiles>

```

## Type

**SPManifestFile**
  
## Elements and attributes

The following sections describe attributes, child elements, and parent elements.

### Attributes

|**Attribute**|**Type**|**Description**|
|:-----|:-----|:-----|
|**Name** <br/> |xs:string  <br/> |Optional. Name of the SystemData.xml file.  <br/> |
   
### Child elements

None
   
### Parent elements

- [ManifestFiles element (DeploymentSystemData)](manifestfiles-element-deploymentsystemdata.md)
   
## See also

- [DeploymentSystemData Schema](deploymentsystemdata-schema.md)

