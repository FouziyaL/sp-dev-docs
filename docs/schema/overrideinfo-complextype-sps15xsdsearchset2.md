---
title: "OverrideInfo complexType (SPS15XSDSearchSet2)"
description: "Describes the definition, type, element, and attribute information for the OverrideInfo complexType (SPS15XSDSearchSet2)."
manager: arnek
ms.date: 06/10/2022
ms.audience: ITPro
ms.topic: article
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 60c793ca-dd25-005a-f935-8725ad403ed7
---

# OverrideInfo complexType (SPS15XSDSearchSet2)

 
  
## Type information

|Information|Location|
|:-----|:-----|
|**Namespace**|http://schemas.datacontract.org/2004/07/Microsoft.Office.Server.Search.Administration|
|**Schema file**|schema_Microsoft.Office.Server.Search.Administration.xsd|
|**Extension base**|tns:BaseInfo|
   
## Definition

```XML
<xs:complexType name="OverrideInfo">
    <xs:complexContent>
        <xs:extension base="tns:BaseInfo">
            <xs:sequence>
                <xs:element name="AliasesOverridden" type="xs:boolean" minOccurs="0"></xs:element>
                <xs:element name="ExtraProperties" type="xs:string" minOccurs="0"></xs:element>
                <xs:element name="ManagedPid" type="xs:int" minOccurs="0"></xs:element>
                <xs:element name="MappingsOverridden" type="xs:boolean" minOccurs="0"></xs:element>
                <xs:element name="SchemaId" type="xs:int" minOccurs="0"></xs:element>
                <xs:element name="TokenNormalization" type="xs:boolean" minOccurs="0"></xs:element>
            </xs:sequence>
        </xs:extension>
    </xs:complexContent>
</xs:complexType>

```

## Elements and attributes

If the schema defines specific requirements, such as **sequence**, **minOccurs**, **maxOccurs**, and **choice**, see the definition section. 
  
### Child elements

|**Element**|**Type**|**Description**|
|:-----|:-----|:-----|
|[AliasesOverridden](aliasesoverridden-element-overrideinfo-complextypesps15xsdsearchset2.md) <br/> |xs:boolean  <br/> ||
|[ExtraProperties](extraproperties-element-overrideinfo-complextypesps15xsdsearchset2.md) <br/> |xs:string  <br/> ||
|[ManagedPid](managedpid-element-overrideinfo-complextypesps15xsdsearchset2.md) <br/> |xs:int  <br/> ||
|[MappingsOverridden](mappingsoverridden-element-overrideinfo-complextypesps15xsdsearchset2.md) <br/> |xs:boolean  <br/> ||
|[SchemaId](schemaid-element-overrideinfo-complextypesps15xsdsearchset2.md) <br/> |xs:int  <br/> ||
|[TokenNormalization](tokennormalization-element-overrideinfo-complextypesps15xsdsearchset2.md) <br/> |xs:boolean  <br/> ||
   
### Attributes

None.
  

