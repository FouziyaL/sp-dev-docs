---
title: "RowLimitExceeded element (DeploymentManifest - SPWebPart)"
description: "RowLimitExceeded element (DeploymentManifest - SPWebPart) represents the means for displaying overflow data when a row limit is exceeded."
manager: soliver
ms.date: 06/14/2022
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 5fe03d39-4800-4333-ab03-377c6fa3871b
---

# RowLimitExceeded element (DeploymentManifest - SPWebPart)

**Applies to:** SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013 
  
Represents the means for displaying overflow data when a row limit on a specified instance of a Windows SharePoint Services 3.0 web part object is exceeded.

## Definition

```XML
DECLARATION
<xs:element name="RowLimitExceeded" minOccurs="0" maxOccurs="unbounded" />

USAGE
<WebPart>
        <RowLimitExceeded />
</ WebPart >

```

## Type

xs:string
  
## Elements and attributes

The following sections describe attributes, child elements, and parent elements.

### Attributes

None
   
### Child elements

None
   
### Parent elements

- [WebPart element (DeploymentManifest)](webpart-element-deploymentmanifest.md)
   
## See also

- [DeploymentManifest Schema](deploymentmanifest-schema.md)

