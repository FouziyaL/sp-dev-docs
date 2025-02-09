---
title: Workflow actions available using the workflow interop bridge
description: Contains a concise list of workflow actions in SharePoint 2010 that are available to SharePoint workflows by using the workflow interop bridge.
ms.date: 06/07/2022
ms.prod: sharepoint
ms.assetid: a8903440-ff8f-41a4-8c2a-5dbe12c07cfb
ms.localizationpriority: medium
---


# Workflow actions available using the workflow interop bridge
Contains a concise list of workflow actions in SharePoint 2010 that are available to SharePoint workflows by using the workflow interop bridge.

> [!NOTE]
> SharePoint 2010 workflows have been retired since August 1, 2020 for new tenants and removed from existing tenants on November 1, 2020. If you’re using SharePoint 2010 workflows, we recommend migrating to Power Automate or other supported solutions. For more info, see [SharePoint 2010 workflow retirement](https://support.microsoft.com/office/sharepoint-2010-workflow-retirement-1ca3fff8-9985-410a-85aa-8120f626965f).

## Workflow actions for the interop bridge
<a name="bkm_wfactions"> </a>

The SharePoint workflow infrastructure is built on Windows Workflow Foundation (WF) 4 and therefore executes workflows in Microsoft Azure. For this reason, some actions from SharePoint 2010 workflows are available in SharePoint only when using the  [SharePoint workflow interop ](sharepoint-workflow-fundamentals.md#bkm_InteropBridge). 
  
    
    
The following actions are available only when you use the workflow interop bridge.
  
    
    

- Add List Item Permissions
    
  
- Assign a Form to a Group
    
  
- Assign a To-do Item
    
  
- Capture a version of the Document Set
    
  
- Collect Data from a User
    
  
- Copy List Item
    
  
- Declare Record
    
  
- Inherit List Item Parent Permissions
    
  
- Lookup Manager of a User
    
  
- Remove List Item Permissions
    
  
- Replace List Item Permissions
    
  
- Send Document Set to Repository
    
  
- Set Content Approval Status
    
  
- Set Content Approval Status for the Document Set
    
  
- Set Workflow Status
    
  
- Start Approval Process
    
  
- Start Custom Task Process
    
  
- Start Document Set Approval Process
    
  
- Start Feedback Process
    
  
- Undeclare Record
    
  

## Conditions and blocks
<a name="bkm_wfconditions"> </a>

 **Conditions**
  
    
    

- If current item field equals value
    
  
- Check list item permission levels
    
  
- Check list item permissions
    
  
 **Blocks**
  
    
    

- Impersonation block
    
  

## See also
<a name="bkm_addlresources"> </a>


-  [Workflow actions quick reference (SharePoint Workflow platform)](workflow-actions-quick-reference-sharepoint-workflow-platform.md)
    
  
-  [SharePoint workflow interop ](sharepoint-workflow-fundamentals.md#bkm_InteropBridge)
    
  
-  [Workflow development in SharePoint Designer and Visio](workflow-development-in-sharepoint-designer-and-visio.md)
    
  
-  [Set up and configure SharePoint Workflow Manager](set-up-and-configure-sharepoint-workflow-manager.md)
    
  

