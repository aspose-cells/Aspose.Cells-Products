---
title: 通过 Java 创建 Excel 文件
url: /zh/java/assembly/
description: 使用 Java 电子表格库从模板工作表生成 Microsoft Excel 电子表格
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通过 Java 创建基于 Excel 模板的报告" h2="根据基于 Java 的应用程序中的预定义模板生成批量 Excel 文件报告。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel 库](/cells/java/) 支持生成基于模板的 Excel 文件以生成批量报告。大多数情况下都需要它，例如创建费用挑战、结果卡和患者记录等。模板是预定义的模式。 Java 下面的代码会生成与已填充数据的模板文档相同的批量 excel 文件。支持的文件格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="基于预先设计的 Excel 模板创建报告" %}}

使用 JavaAssembly API，开发人员可以通过包含以下代码片段轻松编写批量报告生成代码。 API 提供 [导入数据](https://docs.aspose.com/cells/java/import-and-export-data/) 来自不同来源的功能并根据该数据创建 Excel 文档。对于基于模板的模式，API 提供了一个 [WorkbookDesigner 类](https://apireference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner) 表示设计器工作表。过程是，创建它的对象并用它来打开模板文件。设置数据源，可以是 Array、DataTable、Json 等。处理它以导入数据并以所需格式保存文件。程序员可以将数据组装成其他文件格式的报告，包括 XLS、XLSX、XLSB、XLSM、ODS，如下所列链接。



{{% blocks/products/pf/feature-page-code h3="Java 创建 Excel 报告的代码" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}