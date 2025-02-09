---
title: "WebParts Element (DeploymentManifest)"
manager: soliver
ms.date: 06/15/2022
description: Describes WebParts Element (DeploymentManifest) and includes information on elements and attributes.
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: f0392a4d-7b83-461b-83e7-797ab37e6572
---

# WebParts Element (DeploymentManifest)

**Applies to:** SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013 
  
Represents a collection of SharePoint Foundation web part (**SPWebPart**) object instances.

## Definition

```XML
DECLARATION
<xs:element name="WebParts" type="SPWebPartCollection" minOccurs="0" maxOccurs="1" />

USAGE
<File>
   <WebParts>
      <WebPart />
   </WebParts>
</File>

```

## Type

[SPWebPartCollection](https://msdn.microsoft.com/library/Microsoft.SharePoint.SPWebPartCollection.aspx)
  
## Elements and attributes

The following sections describe attributes, child elements, and parent elements.

### Attributes

None
   
### Child elements

[WebPart Element (DeploymentManifest)](webpart-element-deploymentmanifest.md)
   
### Parent elements

[File Element (DeploymentManifest - SPGenericObject)](file-element-deploymentmanifestspgenericobject.md)
   
## See also

- [SPWebPartCollection](https://msdn.microsoft.com/library/Microsoft.SharePoint.SPWebPartCollection.aspx)
- [DeploymentManifest Schema](deploymentmanifest-schema.md)

