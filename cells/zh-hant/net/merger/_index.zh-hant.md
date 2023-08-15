---
title: Excel文件合併 API .NET C#
description: 只需幾行 C# 代碼即可連接 Excel 和 OpenOffice 電子表格文件。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 文件合併 via .NET" h2="使用 C# 代碼將 2 個或多個 Excel 文件合併到一個電子表格中" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 庫](/cells/zh-hant/net/)提供多種方式將工作簿與各種類型的內容（如公式、數據、圖像、圖表等）組合到單個電子表格文件中。支持的文件格式包括 XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、TSV 等。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 文件與圖像和圖表合併" %}}
組合 2 個包含圖像和圖表的 Excel 文件的最簡單方法是調用[工作簿.合併](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine)方法。它允許將類似類型的 Excel 文件合併到單個電子表格中。
{{% blocks/products/pf/feature-page-code h3="C# 合併Excel文件的代碼" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="合併多個 Excel 文件" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles)方法支持將Excel文件的數據、樣式和公式合併到相同格式的新電子表格中。這是使用緩存合併多個文件的有效方法。
{{% blocks/products/pf/feature-page-code h3="C# 合併多個Excel文件的代碼" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="通過複製工作表合併 Excel 文件" %}}
[工作表.副本](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index)可用於將數據和格式從源工作表複製到工作簿內或工作簿之間的另一個工作表。該方法將源工作表對像作為參數。
{{% blocks/products/pf/feature-page-code h3="C# 跨 Excel 文件複製工作表的代碼" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的合併格式" subTitle="使用 C#，還可以合併許多其他文件格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/csv/" name="CSV" description="逗號分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/html/" name="HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/mhtml/" name="MHTML" description="網頁存檔格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/ods/" name="ODS" description="OpenDocument 電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/tsv/" name="TSV" description="製表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/txt/" name="TXT" description="文本文檔" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xls/" name="XLS" description="Excel 二進制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsb/" name="XLSB" description="二進制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsm/" name="XLSM" description="電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlt/" name="XLT" description="Microsoft Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xltm/" name="XLTM" description="Excel 宏啟用模板" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
