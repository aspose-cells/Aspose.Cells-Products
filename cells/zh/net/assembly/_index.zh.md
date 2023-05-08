---
title: 通过 C# 生成 Excel 文件
description: 使用 C# 代码从模板表生成 Microsoft Excel 电子表格
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 基于 Excel 模板的文件创建 via .NET" h2="基于基于 .NET 的应用程序中的预定义模板生成 Excel 文件报告" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 库](/cells/zh/net/)支持生成基于模板的 Excel 文件，用于批量报告生成。模板是预先设计的格式，用于创建相同模式的报告。 .NET 代码创建了一个新的excel文件，与填充了数据的模板文件一样。支持的文件格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="基于预先设计的 Excel 模板创建报告" %}}

使用 .NET Assembly API 可以很容易地自动化创建相同模式文件的过程。有不同的方法[导入数据](https://docs.aspose.com/cells/net/import-data-into-worksheet/#importing-data-from-json)并生成Excel文件。 API提供了[WorkbookDesigner 类](https://reference.aspose.com/cells/net/aspose.cells/workbookdesigner)代表设计师工作表。创建它的对象并用它来打开模板文件。设置数据源，可以是DataTable、Array、Json文件等。处理它以导入数据并以所需格式保存包含数据的文件。程序员可以通过下面列出的链接将数据组合成其他文件格式的报告。



{{% blocks/products/pf/feature-page-code h3="C# 生成 Excel 报告的代码" %}}

{{< gist "aspose-com-gists" "5c193070f1b6acdc3eed001f52eadbc2" "generate-excel-reports.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Generate" afterslug="Reports" >}}
