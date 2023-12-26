---
title: Excel檔案合併 API .NET C#
description: 只需幾行 C# 程式碼即可連接 Excel 和 OpenOffice 電子表格檔案。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 檔案合併 via .NET" h2="使用 C# 代碼將 2 個或多個 Excel 檔案合併到一個電子表格中" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 庫](/cells/zh-hant/net/)提供多種方式將工作簿與各種類型的內容（如公式、資料、圖像、圖表等）組合到單一電子表格檔案中。支援的文件格式包括 XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、0111838383838。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 檔案與影像和圖表合併" %}}
組合 2 個包含圖像和圖表的 Excel 文件的最簡單方法是調用[工作簿.合併](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine)方法。它允許將類似類型的 Excel 檔案合併到單一電子表格中。
{{% blocks/products/pf/feature-page-code h3="C# 合併Excel檔案的程式碼" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="合併多個 Excel 文件" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles)方法支援將Excel檔案的資料、樣式和公式合併到相同格式的新電子表格中。這是使用快取合併多個文件的有效方法。
{{% blocks/products/pf/feature-page-code h3="C# 合併多個Excel檔案的程式碼" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="透過複製工作表合併 Excel 文件" %}}
[工作表.副本](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index)可用於將資料和格式從來源工作表複製到工作簿內或工作簿之間的另一個工作表。此方法將來源工作表物件作為參數。
{{% blocks/products/pf/feature-page-code h3="C# 跨 Excel 檔案複製工作表的程式碼" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="其他支援的合併格式" subTitle="使用 C#，還可以合併許多其他文件格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/csv/" name="CSV" description="逗號分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/html/" name="HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/mhtml/" name="MHTML" description="網頁存檔格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/ods/" name="ODS" description="OpenDocument 電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/tsv/" name="TSV" description="製表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/txt/" name="TXT" description="文字文檔" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xls/" name="XLS" description="Excel 二進位格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsb/" name="XLSB" description="二進位 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsm/" name="XLSM" description="試算表文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlt/" name="XLT" description="Microsoft Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xltm/" name="XLTM" description="Excel 巨集啟用模板" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
