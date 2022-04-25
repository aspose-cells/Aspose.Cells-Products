---
title: 在 Java 中將不同的 Excel 文件合併為一個
url: /zh-hant/java/merger/
description: 使用 Java 將 Excel 文件合併到多個工作表或單個工作表中。也可以將 Excel 文檔合併、合併或連接為 PDF、圖像和 HTML。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通過 Java 合併 Excel 文件" h2="使用 Java 代碼將兩個或多個 Excel 文件合併到一個電子表格中" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel 庫](/cells/java/) 提供多種方式將工作簿與各種類型的內容（如公式、圖像、數據、圖表等）組合到單個電子表格文檔中。支持的文件格式包括 XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、TSV 等。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 文件與圖像和圖表相結合" %}}
合併兩個具有圖像和圖表的 Excel 文件的最簡單方法是調用 [工作簿.combine](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)） 方法。它允許將類似類型的 Excel 文件合併到一個電子表格中。
{{% blocks/products/pf/feature-page-code h3="Java 合併 Excel 文件的代碼" %}}

```cs
// 加載第一個 Excel 文件
var book1 = new Workbook("with-charts.xlsx");
// 將第二個 Excel 文件加載到單獨的實例中
var book2 = new Workbook("with-images.xlsx");

// 合併兩個工作簿
book1.combine(book2);
// 保存目標工作簿 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="合併多個 Excel 文件" %}}
[CellsHelper.mergeFiles](https://apireference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) 方法支持將 Excel 文件的數據、樣式和公式合併到相同格式的新電子表格中。這是在使用緩存時合併多個文件的有效方法。 
{{% blocks/products/pf/feature-page-code h3="Java 合併多個 Excel 文件的代碼" %}}

```cs
// 創建一個數組（長度=2）
String[] files = new String[2];
// 指定要合併的文件路徑
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// 合併文件以保存結果
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="通過複製工作表合併 Excel 文件" %}}
[工作表.copy](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)可用於將數據和格式從源工作表複製到工作簿內或工作簿之間的另一個工作表。該方法將源工作表對像作為參數。
{{% blocks/products/pf/feature-page-code h3="Java 在工作簿之間複製工作表的代碼" %}}

```cs
// 創建工作簿。
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// 創建另一個工作簿。
Workbook excelWorkbook1 = new Workbook();

// 將第一本書的第一頁複製到第二本書中。
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// 保存文件。
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}