---
title: Excel 文件註釋 NET C#
description: 只需幾行 C# 代碼即可添加或刪除 Excel 和 OpenOffice 電子表格的數據註釋。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="刪除 Microsoft<sup>&reg;</sup> Excel 文件註釋 via .NET" h2="在基於 .NET 的應用程序中使用 C# 代碼添加或刪除 Excel 文件註釋。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 庫](/cells/zh-hant/net/)通過添加、訪問和刪除註釋來支持在單元格級別管理註釋。使用單元格級別的評論，可以為最終用戶存儲相關信息。支持的文件格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件數據註釋" %}}
管理工作表中的評論 - 在 MS Excel 中，一張工作表的評論數量沒有任何限制。一個人可以添加盡可能多的應用程序需求。我們將使用[評論類](https://reference.aspose.com/cells/net/aspose.cells/comment)對於所有這些功能。

+ 使用工作簿類對象加載 Excel 文件
訪問相關的工作表及其相關的 Cell 索引
+ 使用 Cell Id 調用 RemoveAt 將其刪除
 使用[備註屬性](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note)用於添加評論內容
調用 RemoveAt 方法比較前後保存工作簿

{{% blocks/products/pf/feature-page-code h3="C# 訪問、插入和刪除 Excel 文件的代碼 Cell 評論" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
