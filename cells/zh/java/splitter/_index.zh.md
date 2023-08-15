---
title: 将 Excel 电子表格拆分为 Java 中的工作表
description: Java 源代码，解释如何使用 Java Excel 库将 Microsoft Excel 文件拆分为多个文档
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 文件分割 via Java" h2="在基于 Java 的应用程序中将 Excel 电子表格拆分为工作表" >}}
{{% blocks/products/pf/feature-page-summary %}}
有多种场景，当需要拆分 Excel 文件（例如包含学生数据的电子表格）并为每个学生分配单个工作表时。并且需要将每个学生的工作表拆分为一个单独的文件。要自动化它 via Java 应用程序，[Java Excel API](/cells/zh/java/)是否可以按工作表拆分 Excel 文档。支持的格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 文档拆分为多个文件" %}}

将 Excel 文件拆分为工作表的最简单方法是访问所有工作表，遍历每个工作表并以所需格式一张一张保存。为了加载工作表，API 提供[练习册](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)班级。[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count)方法获取总页数。迭代每个工作表并使用[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get)用于访问特定工作表。使用以下命令将选定的工作表数据移动到新创建的 Workbook 类对象中[复制方法](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)）。最后保存成需要的格式。

{{% blocks/products/pf/feature-page-code h3="Java 分割Excel文件的代码" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 工作表拆分为多个窗格" %}}

API还提供了将Excel工作表拆分为不同窗格的功能。过程是，使用 Workbook 类加载文件。通过提供其索引来选择第一个工作表或任何所需的工作表。调用具有相关单元格索引作为参数的setActiveCell。最后通过调用 split() 方法将工作表窗口拆分为不同的窗格。

{{% blocks/products/pf/feature-page-code h3="Java 将 Excel 工作表拆分为窗格视图的代码" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
