---
title: 通過 Java 的 Excel 文件註釋
url: /zh-hant/java/annotation/
description: 使用 Java 庫添加或刪除 Excel 和 OpenOffice 電子表格的數據註釋。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 Java 管理 Microsoft<sup>&reg;</sup> Excel 文件註釋" h2="在基於 Java 的應用程序中插入簡單的註釋註釋或刪除 Excel 電子表格單元級註釋。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[JavaExcel API](/cells/java/) 通過添加、訪問和刪除註釋，支持在單元格級別管理註釋。 API 提供 [評論](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [評論集合](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [線程評論](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) 和 [ThreadedCommentCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) 用於處理各方面的意見。
支持的文件格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件數據註釋" %}}
管理工作表中的評論 - 在 MS Excel 中，一張工作表的評論數量沒有任何限制。一個可以添加盡可能多的應用程序要求。添加評論的過程是，創建 [工作簿](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 類對像或使用 Workbook 類加載現有文件。使用 getComments() 訪問它的所有評論。獲取單元格索引並使用 [設置註釋](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) 用於插入評論。此外，API 能夠刪除所有評論。 

{{% blocks/products/pf/feature-page-code h3="Java 在 Excel 文件中添加註釋的代碼" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java 刪除 Excel 文件中的註釋的代碼" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}