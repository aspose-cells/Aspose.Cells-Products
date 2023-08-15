---
title: Excel 文件注释 via Java
description: 使用 Java 库添加或删除 Excel 和 OpenOffice 电子表格的数据注释。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="管理 Microsoft<sup>&reg;</sup> Excel 文件注释 via Java" h2="在基于 Java 的应用程序中插入简单注释以进行注释或删除 Excel 电子表格单元格级注释。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/zh/java/)通过添加、访问和删除注释，支持在单元格级别管理注释。 API提供[评论](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [评论收藏](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [线索评论](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment)和[线程化评论集合](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection)用于处理各方面的意见。
支持的文件格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件数据注释" %}}
管理工作表中的注释 - MS Excel 中一个工作表的注释数量没有任何限制。人们可以根据应用程序的需要添加任意数量的内容。添加评论的过程是，创建[练习册](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)类对象或使用 Workbook 类加载现有文件。使用 getComments() 访问其所有评论。获取单元格索引并使用[设置注释](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note)用于插入评论。此外，API可以删除所有评论。

{{% blocks/products/pf/feature-page-code h3="Java 在 Excel 文件中添加注释的代码" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java 删除 Excel 文件中注释的代码" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
