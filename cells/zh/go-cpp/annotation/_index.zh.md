---
title: 使用 Go 语言通过 C++ 添加或删除 Excel 文件注释
description: 使用 Go 通过 C++ 库添加或删除 Excel 和 OpenOffice 电子表格的数据注释。
keywords: [Go via C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="使用 C++ 通过 Go 管理 MicrosoftExcel 文件注释" h2="通过基于 C++ 的应用程序在 Go 中添加或删除用于注释或评论的简单笔记。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[请联系 C++ Excel API](/cells/zh/go-cpp/)提供对单元格级别注释管理的支持，包括添加、访问和删除注释。API 提供[评论](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/)和[评论集](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/)也[GetComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/getcomments/)用于处理各个方面的评论。支持的 Excel 格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件数据注释" %}}
操作工作表中的批注 - 在 MS Excel 中，工作表中的批注数量没有限制。您可以根据实际应用需要插入任意数量的批注。插入批注的过程如下：创建批注[工作簿](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/)使用类对象加载现有文件并选择要添加注释的工作表。使用 `getComments()` 获取所有注释。使用 `addcomments()` 添加注释。[添加(const char16_t* cellName)](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/add/)方法。获取单元格索引并使用[SetNote](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/setnote/)用于插入评论。此外，API 可以删除所有评论。以下是一些方法：[ClearComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/clearcomments/)清除设计表格中的所有注释。此外，***移除***删除指定索引或指定名称的元素的方法。

{{% blocks/products/pf/feature-page-code h3="使用代码 C++ 在 Excel 文件中添加注释" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-comment-in-excel.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
