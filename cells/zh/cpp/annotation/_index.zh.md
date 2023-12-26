---
title: 通过 C++ 添加或删除 Excel 文件注释
description: 使用 C++ 库添加或删除 Excel 和 OpenOffice 电子表格的数据注释注释。
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C++ 管理 Microsoft<sup>&reg;</sup> Excel 文件注释" h2="在基于 C++ 的应用程序中添加或删除注释或评论的简单注释。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/zh/cpp/)通过添加、访问和删除注释，支持在单元格级别管理注释。 API提供[评论](https://reference.aspose.com/cells/cpp/aspose.cells/comment/)和[评论收藏](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/)也[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)用于处理各方面的意见。支持的 Excel 格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件数据注释" %}}
操作工作表中的注释 - MS Excel 中一张工作表的注释数量不受限制。人们可以根据应用程序的需要插入尽可能多的内容。插入评论的过程是，创建[练习册](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)类对象来加载现有文件并选择要在其中添加注释的工作表。使用 getComments() 获取其所有评论。使用添加评论[添加(const char16_t* 单元格名称)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/)方法。获取单元格索引并使用[设置注释](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/)用于插入评论。此外，API可以删除所有评论。其中几个方法是[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/)清除设计器电子表格中的所有注释。而且，***删除于***方法删除指定索引处或具有指定名称的元素。

{{% blocks/products/pf/feature-page-code h3="C++ 在 Excel 文件中添加注释的代码" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
