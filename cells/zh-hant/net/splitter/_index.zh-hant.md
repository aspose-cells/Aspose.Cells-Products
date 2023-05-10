---
title: 在 C# 中明智地拆分 Excel 工作表
description: C# 解釋如何在 Visual C#.NET 應用程序中將 Microsoft Excel 文件拆分為多個文件的源代碼
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 文件拆分 via .NET" h2="在基於 .NET 的應用程序中使用 C# 代碼將單個 Excel 文檔拆分為不同的文件" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 庫](/cells/zh-hant/net/)能夠在基於 .NET 的應用程序中將 Excel 文檔拆分為多個電子表格。支持的文件格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 文檔拆分為多個文件" %}}
明智地拆分 Excel 文件的最簡單方法是，通過訪問所有工作表[工作表](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) 遍歷每個工作表並調用[複製](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)方法。最後保存到指定路徑。

 + 使用完整路徑加載 Excel 文件[練習冊類](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ 遍歷每張紙
創建一個新的工作簿類對象
 通過複製工作表[複製方法](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
調用 Save() 方法並傳遞具有相關 SaveFormat 的文件名（完整路徑）。

{{% blocks/products/pf/feature-page-code h3="C# 拆分 Excel 文件的代碼" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 工作表拆分為窗格" %}}

為了將工作表窗口拆分為多個窗格，API 提供了[分割法](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split)工作表類，提供工作表的拆分視圖。刪除拆分視圖 API 提供[RemoveSplit 方法](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit).最後保存到指定路徑。

{{% blocks/products/pf/feature-page-code h3="C# 拆分 Excel 工作表窗口的代碼" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# 刪除拆分平移視圖的代碼" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
