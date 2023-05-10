---
title: Excel 文件注释来自 C++
description: 添加或删除 Excel 和 OpenOffice 电子表格的数据注释注释与 C++ 库。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C++ 管理 Microsoft<sup>&reg;</sup> Excel 文件注释" h2="在基于 C++ 的应用程序中添加或删除用于注释或评论的简单注释。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/zh/cpp/)通过添加、访问和删除注释来支持在单元格级别管理注释。 API提供[我评论](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment)和[评论集](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection)也[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)用于处理各方面的评论。支持的 Excel 格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件数据注释" %}}
操作工作表中的注释 - 在 MS Excel 中，一张工作表的注释数量不受限制。一个人可以插入尽可能多的应用程序需要。插入评论的过程是，创建[工作簿](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)类对象以加载现有文件并选择要在其中添加注释的工作表。使用 getComments() 获取它的所有评论。使用添加评论[添加](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)（侵入式指针< Aspose::Cells::Systems::String >单元格名称）方法。获取单元格索引并使用[设置笔记](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580)用于插入评论。此外，API 能够删除所有评论。很少有方法是[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3)清除设计器电子表格中的所有评论。而且，[移除位置](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)（侵入式指针< Aspose::Cells::Systems::String >name) 方法删除指定索引处或具有指定名称的元素。

{{% blocks/products/pf/feature-page-code h3="C++ 在 Excel 文件中添加注释的代码" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
