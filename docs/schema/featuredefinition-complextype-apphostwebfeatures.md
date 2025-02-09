---
title: FeatureDefinition complexType
manager: soliver
ms.date: 06/13/2022
description: Describes FeatureDefinition complexType and includes information on elements and attributes.
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: ab1de98a-64f7-c8d1-0b64-7650cb100167
---

# FeatureDefinition complexType 

(AppHostWebFeatures)

> [!NOTE] 
> The string `app` appears as part of or all of some element, attribute, and file names because SharePoint Add-ins were originally called "apps for SharePoint." To ensure backward compatibility, the schemas have not been changed.

## Type information

| Information | Location |
|---|---|
| **Namespace**  | `http://schemas.microsoft.com/sharepoint/` |
| **Schema file**  | apphostwebfeatures.xsd |
| **Extension base**  | None |

## Definition

```XML
    <xs:complexType name="FeatureDefinition">
        <xs:all>
            <xs:element name="ElementManifests" type="ElementManifestReferences" minOccurs="0" maxOccurs="1"></xs:element>
            <xs:element name="Properties" type="FeaturePropertyDefinitions" minOccurs="0" maxOccurs="1"></xs:element>
            <xs:element name="ActivationDependencies" type="FeatureActivationDependencyDefinitions" minOccurs="0" maxOccurs="1"></xs:element>
            <xs:element name="UpgradeActions" type="UpgradeActionsDefinition" minOccurs="0" maxOccurs="1"></xs:element>
        </xs:all>
        <xs:attribute name="Id" type="UniqueIdentifier" use="required" />
        <xs:attribute name="Title" type="LocalizableString" />
        <xs:attribute name="Description" type="LocalizableString" />
        <xs:attribute name="Version" type="FeatureVersion" />
        <xs:attribute name="Scope" type="FeatureScope" use="required" />
        <xs:attribute name="ReceiverAssembly" type="AssemblyStrongName" />
        <xs:attribute name="ReceiverClass" type="AssemblyClass" />
        <xs:attribute name="Creator" type="LocalizableString" />
        <xs:attribute name="DefaultResourceFile" type="xs:string" />
        <xs:attribute name="Hidden" type="TRUEFALSE" />
        <xs:attribute name="SolutionId" type="UniqueIdentifier" />
        <xs:attribute name="ActivateOnDefault" type="TRUEFALSE" />
        <xs:attribute name="AutoActivateInCentralAdmin" type="TRUEFALSE" />
        <xs:attribute name="AlwaysForceInstall" type="TRUEFALSE" />
        <xs:attribute name="RequireResources" type="TRUEFALSE" />
        <xs:attribute name="ImageUrl" type="RelativeFilePath" use="optional" />
        <xs:attribute name="ImageUrlAltText" type="LocalizableString" use="optional" />
        <xs:attribute name="UIVersion" type="UIVersion" />
    </xs:complexType>
```

## Elements and attributes

If the schema defines specific requirements, such as **sequence**, **minOccurs**, **maxOccurs**, and **choice**, see the definition section.

### Child elements

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
<td align="left"><p><a href="activationdependencies-element-featuredefinition-complextypeapphostwebfeatures.md">ActivationDependencies</a></p></td>
<td align="left"><p><a href="featureactivationdependencydefinitions-complextype-apphostwebfeatures.md">FeatureActivationDependencyDefinitions</a></p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p><a href="elementmanifests-element-featuredefinition-complextypeapphostwebfeatures.md">ElementManifests</a></p></td>
<td align="left"><p><a href="elementmanifestreferences-complextype-apphostwebfeatures.md">ElementManifestReferences</a></p></td>
<td align="left"><p></p></td>
</tr>
<tr class="odd">
<td align="left"><p><a href="properties-element-featuredefinition-complextypeapphostwebfeatures.md">Properties</a></p></td>
<td align="left"><p><a href="featurepropertydefinitions-complextype-apphostwebfeatures.md">FeaturePropertyDefinitions</a></p></td>
<td align="left"><p></p></td>
</tr>
<tr class="even">
<td align="left"><p><a href="upgradeactions-element-featuredefinition-complextypeapphostwebfeatures.md">UpgradeActions</a></p></td>
<td align="left"><p><a href="upgradeactionsdefinition-complextype-apphostwebfeatures.md">UpgradeActionsDefinition</a></p></td>
<td align="left"><p></p></td>
</tr>
</tbody>
</table>

<br/>

### Attributes

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="10%" />
<col width="30%" />
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
<td align="left"><p>ActivateOnDefault</p></td>
<td align="left"><p>TRUEFALSE</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the TRUEFALSE type.</p></td>
</tr>
<tr class="even">
<td align="left"><p>AlwaysForceInstall</p></td>
<td align="left"><p>TRUEFALSE</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the TRUEFALSE type.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>AutoActivateInCentralAdmin</p></td>
<td align="left"><p>TRUEFALSE</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the TRUEFALSE type.</p></td>
</tr>
<tr class="even">
<td align="left"><p>Creator</p></td>
<td align="left"><p>LocalizableString</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the LocalizableString type.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>DefaultResourceFile</p></td>
<td align="left"><p>xs:string</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the xs:string type.</p></td>
</tr>
<tr class="even">
<td align="left"><p>Description</p></td>
<td align="left"><p>LocalizableString</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the LocalizableString type.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>Hidden</p></td>
<td align="left"><p>TRUEFALSE</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the TRUEFALSE type.</p></td>
</tr>
<tr class="even">
<td align="left"><p>Id</p></td>
<td align="left"><p>UniqueIdentifier</p></td>
<td align="left"><p>required</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the UniqueIdentifier type.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>ImageUrl</p></td>
<td align="left"><p>RelativeFilePath</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the RelativeFilePath type.</p></td>
</tr>
<tr class="even">
<td align="left"><p>ImageUrlAltText</p></td>
<td align="left"><p>LocalizableString</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the LocalizableString type.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>ReceiverAssembly</p></td>
<td align="left"><p>AssemblyStrongName</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the AssemblyStrongName type.</p></td>
</tr>
<tr class="even">
<td align="left"><p>ReceiverClass</p></td>
<td align="left"><p>AssemblyClass</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the AssemblyClass type.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>RequireResources</p></td>
<td align="left"><p>TRUEFALSE</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the TRUEFALSE type.</p></td>
</tr>
<tr class="even">
<td align="left"><p>Scope</p></td>
<td align="left"><p><a href="featurescope-simpletype-apphostwebfeatures.md">FeatureScope</a></p></td>
<td align="left"><p>required</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the FeatureScope type.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>SolutionId</p></td>
<td align="left"><p>UniqueIdentifier</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the UniqueIdentifier type.</p></td>
</tr>
<tr class="even">
<td align="left"><p>Title</p></td>
<td align="left"><p>LocalizableString</p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the LocalizableString type.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>UIVersion</p></td>
<td align="left"><p><a href="uiversion-simpletype-apphostwebfeatures.md">UIVersion</a></p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the UIVersion type.</p></td>
</tr>
<tr class="even">
<td align="left"><p>Version</p></td>
<td align="left"><p><a href="featureversion-simpletype-apphostwebfeatures.md">FeatureVersion</a></p></td>
<td align="left"><p>optional</p></td>
<td align="left"><p></p></td>
<td align="left"><p>Values of the FeatureVersion type.</p></td>
</tr>
</tbody>
</table>

<br/>

<br/>







