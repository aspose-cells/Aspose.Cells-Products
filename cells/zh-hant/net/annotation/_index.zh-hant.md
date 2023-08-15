---
title: Excel 文件註釋 NET C#
description: 只需幾行 C# 代碼即可添加或刪除 Excel 和 OpenOffice 電子表格的數據註釋。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="刪除 Microsoft<sup>&reg;</sup> Excel 文件註釋 via .NET" h2="在基於 .NET 的應用程序中使用 C# 代碼添加或刪除 Excel 文件註釋。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 庫](/cells/zh-hant/net/)通過添加、訪問和刪除註釋，支持在單元格級別管理註釋。使用單元級別的註釋，可以為最終用戶存儲相關信息。支持的文件格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件數據註釋" %}}
管理工作表中的註釋 - MS Excel 中一個工作表的註釋數量沒有任何限制。人們可以根據應用程序的需要添加任意數量的內容。我們將使用[評論類](https://reference.aspose.com/cells/net/aspose.cells/comment)對於所有這些功能。

+ 使用 Workbook 類對象加載 Excel 文件
訪問相關工作表及其相關 Cell 索引
使用 Cell Id 調用RemoveAt將其刪除
 使用[注意屬性](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note)用於添加評論內容
保存調用RemoveAt方法前後的工作簿進行比較

{{% blocks/products/pf/feature-page-code h3="C# 訪問、插入和刪除 Excel 文件的代碼 Cell 評論" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
