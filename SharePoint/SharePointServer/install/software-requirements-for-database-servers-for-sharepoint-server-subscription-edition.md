---
title: "Software requirements for Database Servers for SharePoint Server Subscription Edition"
ms.reviewer: 
ms.author: v-nsatapathy
author: nimishasatapathy
manager: serdars
ms.date: 7/10/2021
audience: ITPro
f1.keywords:
- NOCSH
ms.topic: conceptual
ms.prod: sharepoint-server-itpro
ms.localizationpriority: medium
ms.collection:
- IT_Sharepoint_Server
- IT_Sharepoint_Server_Top
ms.assetid: 
description: "Introduces articles that describe software and other requirements for SharePoint Server Subscription Edition."
---

# Software requirements for Database Servers for SharePoint Server Subscription Edition

[!INCLUDE [appliesto-xxx-xxx-xxx-SUB-xxx-md](../includes/appliesto-xxx-xxx-xxx-SUB-xxx-md.md)] 
  
## Operating systems

SharePoint Server supports the following operating systems:

- [Windows Server 2019](https://www.microsoft.com/evalcenter/evaluate-windows-server-2019) Standard or Datacenter
- [Windows Server 2022](https://www.microsoft.com/evalcenter/evaluate-windows-server-2022) Standard or Datacenter

Earlier versions of windows server are not supported. SharePoint server supports both the Standard and Datacenter editions of windows server, as well as both the Windows Server with Desktop Experience and windows server core installation options.

## Database versions

SharePoint Server Subscription Edition supports the following database versions:

- A Standard or Enterprise Edition of SQL Server for Windows that supports database compatibility level 150. This includes SQL Server 2019 CU5 or later and any future version of SQL Server for Windows that supports database compatibility level 150. For more information about database compatibility levels, see [Compatibility Certification](/sql/database-engine/install-windows/compatibility-certification?view=sql-server-ver15&preserve-view=true) and [ALTER DATABASE (Transact-SQL) Compatibility Level](/sql/t-sql/statements/alter-database-transact-sql-compatibility-level?view=sql-server-ver15&preserve-view=true).

- Microsoft Azure SQL Managed Instance (MI). This is only supported if your SharePoint Server farm is hosted in Microsoft Azure. For more information, see [Deploy Azure SQL Managed Instance with SharePoint Servers 2016 and 2019](../administration/deploy-azure-sql-managed-instance-with-sharepoint-servers-2016-2019.md).

> [!NOTE]
> SQL Server products and all future public updates are supported through the SQL Server product lifecycle.

> [!NOTE]
> SQL Server Express is not supported. Azure SQL Database (the non-Managed Instance DBaaS service) is also not supported for any SharePoint databases.

