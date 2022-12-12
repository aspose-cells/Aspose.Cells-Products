---
title: 通过 C++ 的 Excel 文件注释

description: 使用 C++ 库添加或删除 Excel 和 OpenOffice 电子表格的数据注释注释。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C++ 管理 Microsoft<sup>&reg;</sup> Excel 文件注释" h2="在基于 C++ 的应用程序中添加或删除注释或评论的简单注释。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++Excel API](/cells/cpp/) 通过添加、访问和删除注释，支持在单元格级别管理注释。 API 提供 [我评论](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) 和 [ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) 也 [GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) 用于处理各方面的意见。支持的 Excel 格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件数据注释" %}}
处理工作表中的评论 - 在 MS Excel 中，一张工作表的评论数量不受限制。可以根据应用需要插入多少。插入评论的过程是，创建 [工作簿](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 类对象以加载现有文件并选择要在其中添加注释的工作表。使用 getComments() 获取所有评论。添加评论使用 [添加](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > 细胞名称）方法。获取单元格索引并使用 [设置注释](https://reference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) 用于插入评论。此外，API 能够删除所有评论。几种方法是 [清除评论（）](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) 清除设计器电子表格中的所有注释。而且， [删除时间](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) 方法来删除指定索引处或指定名称的元素。

{{% blocks/products/pf/feature-page-code h3="C++ 在 Excel 文件中添加注释的代码" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
