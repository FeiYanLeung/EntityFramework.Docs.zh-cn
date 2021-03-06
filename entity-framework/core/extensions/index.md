---
title: "工具和扩展 - EF Core"
author: ErikEJ
ms.author: divega
ms.date: 7/3/2018
ms.assetid: 14fffb6c-a687-4881-a094-af4a1359a296
ms.technology: entity-framework-core
uid: core/extensions/index
ms.openlocfilehash: 6c8cb3e0d8552f274118e4020b7e2e8009af7e11
ms.sourcegitcommit: fc68321c211aca38f7b9dc3a75677c6ca1b2524b
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/08/2018
---
# <a name="ef-core-tools--extensions"></a>EF Core 工具和扩展

工具和扩展为 Entity Framework Core 提供了额外功能。

> [!IMPORTANT]  
> 扩展由多种源生成，并不会作为 Entity Framework Core 项目的组成部分进行维护。 考虑使用第三方扩展时，请务必评估质量、授权、兼容性、支持等因素，确保其满足要求。

## <a name="tools"></a>工具

### <a name="llblgen-pro"></a>LLBLGen Pro

LLBLGen Pro 是一种实体建模解决方案，包含对 Entity Framework 和 Entity Framework Core 的支持。 借助它可轻松通过 Database First 或 Model First 定义实体模型并将其映射到数据库中，使你可以立即开始编写查询。

[网站](https://www.llblgen.com/)

### <a name="devart-entity-developer"></a>Devart Entity Developer

Devart Entity Developer 是一种用于 ADO.NET 实体框架、NHibernate、LinqConnect、Telerik 数据访问和 LINQ to SQL 的强大 ORM 设计器。 可使用 Model-First 和 Database-First 方法来设计 ORM 模型并为其生成 C# 或 Visual Basic .NET 代码。 它引入了新方法来设计 ORM 模型、提高工作效率并促进数据库应用程序的开发。

[网站](https://www.devart.com/entitydeveloper/)

### <a name="ef-core-power-tools"></a>EF Core Power Tools

Visual Studio 2017 及以上版本扩展。 可从现有数据库或 SQL Server 数据库项目反向 DbContext 和 POCO 类的工程，并采用各种方式可视化和检查 DbContext。

[GitHub wiki](https://github.com/ErikEJ/SqlCeToolbox/wiki/EF-Core-Power-Tools)

## <a name="extensions"></a>扩展

### <a name="microsoftentityframeworkcoreautohistory"></a>Microsoft.EntityFrameworkCore.AutoHistory

Microsoft.EntityFrameworkCore 的一个插件，支持自动记录数据更改历史记录。

[GitHub 存储库](https://github.com/Arch/AutoHistory/)

### <a name="microsoftentityframeworkcoredynamiclinq"></a>Microsoft.EntityFrameworkCore.DynamicLinq

Microsoft.EntityFrameworkCore 的 Dynamic Linq 扩展，添加了异步支持

 [GitHub 存储库](https://github.com/StefH/System.Linq.Dynamic.Core/)

### <a name="efcorepractices"></a>EFCore.Practices

尝试在支持测试的 API 中捕获一些良好做法或最佳做法 - 包括用于扫描 N+1 查询的小框架。

[GitHub 存储库](https://github.com/riezebosch/efcore-practices/tree/master/src/EFCore.Practices/)

### <a name="efsecondlevelcachecore"></a>EFSecondLevelCache.Core

二级缓存库。 二级缓存是一个查询缓存。 EF 命令的结果将存储在该缓存中，这样相同的 EF 命令将从该缓存检索其数据，而不是再次针对数据库进行执行。

[GitHub 存储库](https://github.com/VahidN/EFSecondLevelCache.Core/)

### <a name="detachedentityframework"></a>Detached.EntityFramework

加载和保存整个分离式实体图（具有其子实体和列表的实体）。 灵感来自 [GraphDiff](https://github.com/refactorthis/GraphDiff/)。 此想法也添加了一些插件来简化一些重复任务，例如审计和分页。

[GitHub 存储库](https://github.com/leonardoporro/Detached/)

### <a name="entityframeworkcoreprimarykey"></a>EntityFrameworkCore.PrimaryKey

从任何作为字典的实体中检索主键（包括复合键）。

[GitHub 存储库](https://github.com/NickStrupat/EntityFramework.PrimaryKey/)

### <a name="entityframeworkcorerx"></a>EntityFrameworkCore.Rx

为 Entity Framework 实体的常用可观察对象重新激活扩展包装器。

[GitHub 存储库](https://github.com/NickStrupat/EntityFramework.Rx/)

### <a name="entityframeworkcoretriggers"></a>EntityFrameworkCore.Triggers

使用插入、更新和删除事件将触发器添加到实体中。 每个事件具有三种情况：之前、之后和失败时。

[GitHub 存储库](https://github.com/NickStrupat/EntityFramework.Triggers/)

### <a name="entityframeworkcoretypedoriginalvalues"></a>EntityFrameworkCore.TypedOriginalValues

获取对实体属性的 OriginalValue 的类型化访问权限。 支持简单的和复杂的属性，不支持导航/集合。

[GitHub 存储库](https://github.com/NickStrupat/EntityFramework.TypedOriginalValues/)

### <a name="geco"></a>Geco

Geco 提供一个支持复数形式/单数形式的反向模型生成器，和基于 C# 6.0 内插字符串且在 .Net Core 上运行的可编辑模板。 它还提供一个具有 SQL Merge 脚本的源脚本生成器和一个脚本运行程序。

[Github 存储库](https://github.com/iQuarc/Geco)

### <a name="linqkitmicrosoftentityframeworkcore"></a>LinqKit.Microsoft.EntityFrameworkCore

LinqKit.Microsoft.EntityFrameworkCore 是一组适用于 LINQ to SQL 和 EntityFrameworkCore 高级用户的免费扩展。 支持 Include(...) 和 IDbAsync。

[GitHub 存储库](https://github.com/scottksmith95/LINQKit/)

### <a name="neinlinqentityframeworkcore"></a>NeinLinq.EntityFrameworkCore

NeinLinq.EntityFrameworkCore 提供对以下操作有所帮助的扩展：使用 LINQ 提供程序（例如仅支持一小部分 .NET 函数的 Entity Framework ）、重用函数、重写查询、甚至让它们处于 null safe 状态以及使用可转换谓词和选择器生成动态查询。

[GitHub 存储库](https://github.com/axelheer/nein-linq/)

### <a name="microsoftentityframeworkcoreunitofwork"></a>Microsoft.EntityFrameworkCore.UnitOfWork

Microsoft.EntityFrameworkCore 的一个插件，支持存储库、工作模式单元和多个具有支持的分布式事务的数据库。

[GitHub 存储库](https://github.com/Arch/UnitOfWork/)

### <a name="entityframeworklazyloading"></a>EntityFramework.LazyLoading

EF Core 1.1 延迟加载

[GitHub 存储库](https://github.com/darxis/EntityFramework.LazyLoading)

### <a name="efcorebulkextensions"></a>EFCore.BulkExtensions

用于批量操作（插入、更新、删除）的 EntityFrameworkCore 扩展。

[GitHub 存储库](https://github.com/borisdj/EFCore.BulkExtensions)
