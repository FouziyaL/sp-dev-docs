---
title: "SearchRankingModelConfigurationSettings complexType (SPS15XSDSearchSet3)"
manager: arnek
ms.date: 06/14/2022
ms.audience: ITPro
ms.topic: article
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 2630cc13-d07c-dfc9-d848-4872715a9f09
description: Learn about SearchRankingModelConfigurationSettings complexType (SPS15XSDSearchSet3).
---

# SearchRankingModelConfigurationSettings complexType (SPS15XSDSearchSet3)

 
  
## Type information

|Information|Location|
|:-----|:-----|
|**Namespace** |http://schemas.datacontract.org/2004/07/Microsoft.Office.Server.Search.Portability   |
|**Schema file**  |schema_Microsoft.Office.Server.Search.Portability.xsd  |
|**Extension base**  |None  |
   
## Definition

```XML
<xs:complexType name="SearchRankingModelConfigurationSettings">
    <xs:sequence>
        <xs:element name="RankingModels" type="q7:ArrayOfstring" minOccurs="0"></xs:element>
    </xs:sequence>
</xs:complexType>

```

## Elements and attributes

If the schema defines specific requirements, such as **sequence**, **minOccurs**, **maxOccurs**, and **choice**, see the definition section. 
  
### Child elements

|**Element**|**Type**|**Description**|
|:-----|:-----|:-----|
|[RankingModels](rankingmodels-element-searchrankingmodelconfigurationsettings-complextypesps15xs.md) <br/> |q7:ArrayOfstring  <br/> ||
   
### Attributes

None.
  

