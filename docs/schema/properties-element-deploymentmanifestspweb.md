---
title: "Properties Element (DeploymentManifest - SPWeb)"
description: Describes the Properties element (DeploymentManifest - SPWeb) and provides a definition, the type, and the elements and attributes.
manager: soliver
ms.date: 06/09/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 846e7a27-468e-4b7f-a911-5c923f4e774c
---

# Properties Element (DeploymentManifest - SPWeb)

**Applies to:** SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013 
  
Represents a collection of properties on an instance of a Windows SharePoint Services 3.0 Web ([SPWeb](https://msdn.microsoft.com/library/Microsoft.SharePoint.SPWeb.aspx)) object. 

## Definition

```XML
DECLARATION
<xs:element name="Properties" type="Dictionary" />

USAGE
<Web>
        <Properties
                <Property />
        />
</Web>

```

## Type

[Dictionary](https://msdn.microsoft.com/library/System.Collections.Generic.Dictionary.aspx)
  
## Elements and attributes

The following sections describe attributes, child elements, and parent elements.

### Attributes

None
   
### Child elements

[Property Element (DeploymentManifest)](property-element-deploymentmanifest.md)
   
### Parent elements

[Web Element (DeploymentManifest)](web-element-deploymentmanifest.md)
   
## See also

- [SPWeb](https://msdn.microsoft.com/library/Microsoft.SharePoint.SPWeb.aspx)
- [Dictionary](https://msdn.microsoft.com/library/System.Collections.Generic.Dictionary.aspx)
- [DeploymentManifest Schema](deploymentmanifest-schema.md)

