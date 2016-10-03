---
title: Server Role Upgrade and Migration Matrix for Windows Server 2016
description: "Shows which server roles can be upgraded or migrated to Windows Server 2016."
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.date: 10/03/2016
ms.technology: server-general
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 74aa1da3-7076-4a1f-ad5b-9e17bd46dba2
author: jaimeo
ms.author: jaimeo
manager: dongill
---
# Server role upgrade and migration matrix for Windows Server 2016

>Applies To: Windows Server 2016

The grid on this page explains your server role upgrade and migration options specifically for moving to Windows Server 2016. For individual role migration guides, visit [Migrating Roles and Features in Windows Server](https://technet.microsoft.com/windowsserver/jj554790.aspx). For more information about installation and upgrades, see [Windows Server Installation, Upgrade, and Migration](https://technet.microsoft.com/windowsserver/dn458795).

|Server Role|Upgradeable from Windows Server 2012 R2?|Upgradeable from Windows Server 2012?|Migration Supported?|Can migration be completed without downtime?|  
|-------------------|----------|--------------|--------------|----------|  
|Active Directory Certificate Services|	Yes|	Yes|	Yes|	No|
|Active Directory Domain Services|	Yes|	Yes|	Yes|	Yes|
|Active Directory Federation Services|	No|	No|	Yes|	No (new nodes need to be added to the farm)|
|Active Directory Lightweight Directory Services|	Yes|	Yes|	Yes|	Yes|
|Active Directory Rights Management Services|	Yes|	Yes|	Yes|	No|
|DHCP Server|	Yes|	Yes|	Yes|	Yes|
|DNS Server|	Yes|	Yes|	Yes|	No|
|Failover Cluster|Yes with [Cluster OS Rolling Upgrade](https://technet.microsoft.com/windows-server-docs/failover-clustering/cluster-operating-system-rolling-upgrade) process which includes node Pause-Drain, Evict, upgrade to Windows Server 2016 and rejoin the original cluster. Yes, when the server is removed by the cluster for upgrade and then added to a different cluster.|Not while the server is part of a cluster. Yes, when the server is removed by the cluster for upgrade and then added to a different cluster.	|Yes|No for Windows Server 2012 Failover Clusters. Yes for Windows Server 2012 R2 Failover Clusters with Hyper-V VMs or Windows Server 2012 R2 Failover Clusters running the Scale-out File Server role. See [Cluster OS Rolling Upgrade](https://technet.microsoft.com/windows-server-docs/failover-clustering/cluster-operating-system-rolling-upgrade).|
|File and Storage Services|	Yes|	Yes|	Varies by sub-feature|	No|
|Print and Fax Services|	No|	No|	Yes (Printbrm.exe)|	No|
|Remote Desktop Services|	Yes, for all sub-roles, but mixed mode farm is not supported|	Yes, for all sub-roles, but mixed mode farm is not supported|	Yes|	No|
|Web Server (IIS)|	Yes|	Yes|	Yes|	No|
|Windows Server Essentials Experience|	Yes|	N/A – new feature|	Yes|	No|
|Windows Server Update Services|	Yes|	Yes|	Yes|	No|
|Work Folders|	Yes|	Yes|	Yes|	Yes from WS 2012 R2 cluster when using [Cluster OS Rolling Upgrade](https://technet.microsoft.com/windows-server-docs/failover-clustering/cluster-operating-system-rolling-upgrade).|
