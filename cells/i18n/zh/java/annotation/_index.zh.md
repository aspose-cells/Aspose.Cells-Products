---
title: 通过 Java 的 Excel 文件注释
url: /zh/java/annotation/
description: 使用 Java 库添加或删除 Excel 和 OpenOffice 电子表格的数据注释。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 管理 Microsoft<sup>&reg;</sup> Excel 文件注释" h2="在基于 Java 的应用程序中插入简单的注释注释或删除 Excel 电子表格单元级注释。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[JavaExcel API](/cells/java/) 通过添加、访问和删除注释，支持在单元格级别管理注释。 API 提供 [评论](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [评论集合](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [线程评论](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) 和 [ThreadedCommentCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) 用于处理各方面的意见。
支持的文件格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件数据注释" %}}
管理工作表中的评论 - 在 MS Excel 中，一张工作表的评论数量没有任何限制。一个可以添加尽可能多的应用程序要求。添加评论的过程是，创建 [工作簿](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 类对象或使用 Workbook 类加载现有文件。使用 getComments() 访问它的所有评论。获取单元格索引并使用 [设置注释](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) 用于插入评论。此外，API 能够删除所有评论。 

{{% blocks/products/pf/feature-page-code h3="Java 在 Excel 文件中添加注释的代码" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java 删除 Excel 文件中的注释的代码" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}