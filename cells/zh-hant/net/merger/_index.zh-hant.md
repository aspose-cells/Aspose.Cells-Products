---
title: Excel 文件合併 API .NET C#

description: 只需幾行 C# 代碼即可連接 Excel 和 OpenOffice 電子表格文件。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通過 .NET 合併 Excel 文件" h2="使用 C# 代碼將 2 個或更多 Excel 文件合併到一個電子表格中" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 庫](/cells/net/) 提供多種方式將工作簿與各種類型的內容（如公式、數據、圖像、圖表等）組合到單個電子表格文件中。支持的文件格式包括 XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、TSV 等。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 文件與圖像和圖表相結合" %}}
組合 2 個具有圖像和圖表的 Excel 文件的最簡單方法是調用 [工作簿.組合](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) 方法。它允許將類似類型的 Excel 文件合併到一個電子表格中。
{{% blocks/products/pf/feature-page-code h3="C# 合併 Excel 文件的代碼" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="合併多個 Excel 文件" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) 方法支持將 Excel 文件的數據、樣式和公式合併到相同格式的新電子表格中。這是在使用緩存時合併多個文件的有效方法。 
{{% blocks/products/pf/feature-page-code h3="C# 合併多個 Excel 文件的代碼" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="通過複製工作表合併 Excel 文件" %}}
[工作表.複製](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) 可用於將數據和格式從源工作表複製到工作簿內或工作簿之間的另一個工作表。該方法將源工作表對像作為參數。
{{% blocks/products/pf/feature-page-code h3="C# 跨 Excel 文件複製工作表的代碼" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
