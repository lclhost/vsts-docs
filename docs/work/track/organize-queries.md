---
title: Organize and view queries, create query folders 
titleSuffix: VSTS & TFS  
ms.global_help.title: Organize queries
description: Manage your queries by using favorites and folders in Visual Studio Team Services & Team Foundation Server 
ms.prod: devops
ms.technology: devops-agile
ms.assetid: BAD9F638-3F26-4FE3-8A7D-F5C0793BE8AC  
ms.manager: douge
ms.author: kaelli
author: KathrynEE
ms.topic: conceptual
monikerRange: '>= tfs-2013'
ms.date: 06/21/2018  
---


# Organize queries, add a query folder    

[!INCLUDE [temp](../_shared/version-vsts-tfs-all-versions.md)]

Organize your personal or shared queries by adding a query folder. You can then add queries to or move existing queries into those folders.
 
## Prerequisites
If you're not a member of the Project Administrators group, [get added](../../organizations/security/set-project-collection-level-permissions.md), or have your **Edit project-level information** permission set to **Allow**.  


## Open Queries 

[!INCLUDE [temp](../_shared/new-agile-hubs-feature.md)] 

[!INCLUDE [temp](../_shared/open-queries.md)] 


## Add a query folder, move items into a folder 

::: moniker range="vsts"

You add query folders from the **Work>Queries>All** page.
 
0. Choose **All**. Expand **My Queries** or Shared Queries depending on where you want to add a query folder. 
 
0. To add a folder, choose the ![](../_img/icons/actions-icon.png) actions icon for an existing folder or the top container folder, and choose **New folder**. 

	> [!div class="mx-imgBorder"]  
	> ![Open Actions menu, choose New folder](_img/organize-queries/select-new-folder.png)

0. Enter the name for the folder in the New folder dialog. If you want to change the location of the folder, select it from the Folder drop down menu.  

	<img src="_img/organize-queries/new-folder-dialog.png" alt="Open Actions menu, choose New folder" style="border: 2px solid #C3C3C3;" />

0. To move items into a folder, drag-and-drop a query onto the folder. 

	Optionally, you can click the ![Actions icon](../_img/icons/actions-icon.png)  for an existing query, choose **Edit**, and then choose **Save As**. In the Save query as dialog, choose the folder you want to save the query in. 

	<img src="_img/organize-queries/save-query-as-dialog.png" alt="Save query as dialog" style="border: 2px solid #C3C3C3;" />
  
::: moniker-end
::: moniker range=">= tfs-2013 <= tfs-2018"

You add query folders from the **Work>Queries** page.

0. To add a folder, choose the ![](../_img/icons/context_menu.png) context menu for an existing folder or the top container folder and select **New query folder**. 

	Enter the name for the folder in the New query folder dialog.  

	![New query folder link on queries context menu](_img/set-query-perm-new-folder.png)   

0. To move items into a folder, drag-and-drop a query onto the folder. 

	Optionally, you can choose the ![](../_img/icons/context_menu.png) context icon for an existing query and choose **Rename**. In the Rename query dialog, select the folder you want to save the query in. 

	![Rename query dialog](_img/organize-queries/rename-query-old-experience.png) 

::: moniker-end


<a id="favorite-query">  </a>
::: moniker range=">= tfs-2015"
### Add a query to the dashboard or share it with your team 
To add a query to the home page or a dashboard, open the ![](../_img/icons/actions-icon.png) actions (or ![](_img/22.png) context) menu for the query and [add it to a specific dashboard](../../report/dashboards/dashboards.md) or as a team favorite. 

Share queries with your team by adding them to a folder under the **Shared Queries** container.  To save a query to a Shared Queries folder, get added to the [project administrators group](../../organizations/security/set-project-collection-level-permissions.md) or have your [permissions set for a folder under Shared Queries](set-query-permissions.md). 

You can only add shared queries to dashboards or as team favorites, and only if you have [team administrator or project administrator permissions](../scale/manage-team-assets.md). 

::: moniker-end

## Q & A   
<!-- BEGINSECTION class="md-qanda" -->

### Q: Can I change the owner of a query or folder?

::: moniker range=">= tfs-2015"
**A:** No. You can only enable permissions for users and groups from the permissions window for the query or folder.
::: moniker-end

::: moniker range=">= tfs-2013"
**A:** Yes. This is a supported feature from the [query Security dialog](set-query-permissions.md). 
::: moniker-end

### Q: Can I add folders to team favorites?

**A:** No. You can only add folders under **My Queries** and under **Shared Queries**.

### Q: Are the queries and folders I create from the web portal the same as in Team Explorer?

**A:** Yes. You might have to refresh your browser or client to see changes you make in another client.

### Q: Can I move a query or a folder?  

**A:** Yes. In the web portal, choose **Rename** from the context menu. In Visual Studio Team Explorer, simply drag the folder to the new location.  

In Team Explorer for Eclipse, choose **Move** from the context menu and select the folder to which you want to move the item.

<!-- ENDSECTION --> 

## Related articles
- [Query keyboard shortcuts](queries-keyboard-shortcuts.md)
- [Set query permissions](set-query-permissions.md)
- [Set project-level permissions](../../organizations/security/set-project-collection-level-permissions.md)

