---
title: 在 Java 中將不同的 Excel 文件合併為一個文件
description: 使用 Java 將 Excel 檔案合併為多個工作表或單一工作表。將 Excel 文件合併、組合或連接到 PDF、影像和 HTML。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 檔案合併 via Java" h2="使用 Java 程式碼將兩個或多個 Excel 檔案合併到一個電子表格中" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel 庫](/cells/zh-hant/java/)提供多種方式將工作簿與各種類型的內容（如公式、圖像、資料、圖表等）組合到單一電子表格文件中。支援的文件格式包括 XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、0111838383838。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 檔案與影像和圖表合併" %}}
合併兩個包含圖像和圖表的 Excel 文件的最簡單方法是調用[工作簿.組合](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)） 方法。它允許將類似類型的 Excel 檔案合併到單一電子表格中。
{{% blocks/products/pf/feature-page-code h3="Java 合併Excel檔案的程式碼" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="合併多個 Excel 文件" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles)方法支援將Excel檔案的資料、樣式和公式合併到相同格式的新電子表格中。這是使用快取合併多個文件的有效方法。
{{% blocks/products/pf/feature-page-code h3="Java 合併多個Excel檔案的程式碼" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="透過複製工作表合併 Excel 文件" %}}
[工作表.副本](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)可用於將資料和格式從來源工作表複製到工作簿內或工作簿之間的另一個工作表。此方法將來源工作表物件作為參數。
{{% blocks/products/pf/feature-page-code h3="Java 在工作簿之間複製工作表的代碼" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="其他支援的合併格式" subTitle="使用 Java，還可以合併許多其他文件格式，包括.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="逗號分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="網頁存檔格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="OpenDocument 電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="製表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="文字文檔" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Excel 二進位格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="二進位 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="試算表文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel 巨集啟用模板" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
