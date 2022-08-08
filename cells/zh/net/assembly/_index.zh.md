---
title: 通过 C# 生成 Excel 文件
url: /zh/net/assembly/
description: 使用 C# 代码从模板表生成 Microsoft Excel 电子表格
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通过 .NET 创建基于 Excel 模板的文件" h2="根据基于 .NET 的应用程序中的预定义模板生成 Excel 文件报告" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 库](/cells/net/) 支持生成基于模板的 Excel 文件以生成批量报告。模板是预先设计的格式，用于创建相同的模式报告。 .NET 代码创建与已填充数据的模板文档相同的新 excel 文件。支持的文件格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="基于预先设计的 Excel 模板创建报告" %}}

使用 .NETAssembly API 可以轻松自动创建相同的模式文件。有不同的方法可以 [导入数据](https://docs.aspose.com/cells/net/import-data-into-worksheet/#importing-data-from-json) 并生成 Excel 文件。 API 提供了一个 [WorkbookDesigner 类](https://reference.aspose.com/cells/net/aspose.cells/workbookdesigner) 表示设计器工作表。创建它的对象并使用它来打开模板文件。设置数据源，可以是DataTable，Array，Json文件等。处理它以导入数据并以所需格式保存数据文件。程序员可以按照下面列出的链接将数据组装成其他文件格式的报告。



{{% blocks/products/pf/feature-page-code h3="C# 生成 Excel 报告的代码" %}}

{{< gist "aspose-com-gists" "5c193070f1b6acdc3eed001f52eadbc2" "generate-excel-reports.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Generate" afterslug="Reports" >}}