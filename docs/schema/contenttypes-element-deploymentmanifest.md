---
title: "ContentTypes element (DeploymentManifest)"
description: Provides a definition, elements and attributes for the ContentTypes element DeploymentManifest in Sharepoint.
manager: soliver
ms.date: 06/07/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: a24de782-ce49-43f7-ac73-dd844548eba8
---

# ContentTypes element (DeploymentManifest)

**Applies to:** SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013 
  
Represents a container, or collection, of Windows SharePoint Services 3.0 content type specifications for list items.

## Definition

```XML
DECLARATION
<xs:element name="ContentTypes" type="SPContentTypeCollection" minOccurs="0" maxOccurs="1" />

USAGE
<List>
   <ContentTypes />
</List>
```

## Type

[SPContentTypeCollection](https://msdn.microsoft.com/library/Microsoft.SharePoint.SPContentTypeCollection.aspx)
  
## Elements and attributes

The following sections describe attributes, child elements, and parent elements.

### Attributes

None
   
### Child elements

None
   
### Parent elements

[List element (DeploymentManifest)](list-element-deploymentmanifest.md)
   
### Remarks

The collections represented by the **ContentTypes** element are of object instances represented by the [ContentType element (DeploymentManifest)](contenttype-element-deploymentmanifest.md) element. 
  
## See also

- [SPContentType](https://msdn.microsoft.com/library/Microsoft.SharePoint.SPContentType.aspx) 
- [SPContentTypeCollection](https://msdn.microsoft.com/library/Microsoft.SharePoint.SPContentTypeCollection.aspx)
- [DeploymentManifest Schema](deploymentmanifest-schema.md)
- [ContentType element (DeploymentManifest)](contenttype-element-deploymentmanifest.md)

