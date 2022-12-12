---
title: 在 Java 中將 Excel 電子表格拆分為工作表

description: Java 說明如何使用 Java Excel 庫將 Microsoft Excel 文件拆分為多個文檔的源代碼
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通過 Java 拆分 Excel 文件" h2="在基於 Java 的應用程序中將 Excel 電子表格拆分為工作表" >}}
{{% blocks/products/pf/feature-page-summary %}}
有多種場景，當需要拆分 Excel 文件時，例如包含學生數據的電子表格，並為每個學生分配單個工作表。並且需要明智地將每個學生表拆分為一個單獨的文件。要通過 Java 應用程序將其自動化， [JavaExcel API](/cells/java/) 是否可以逐頁拆分 Excel 文檔。支持的格式包括 XLS、XLSX、XLSB、XLSM、ODS。 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 文檔拆分為多個文件" %}}

將 Excel 文件拆分為工作表的最簡單方法是，訪問所有工作表，遍歷每個工作表並以所需格式逐個保存。為了加載工作表，API 提供 [工作簿](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 班級。 [getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) 方法獲取總張數。遍歷每張紙並使用 [getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) 用於訪問特定工作表。通過使用將選定的工作表數據移動到新創建的 Workbook 類對像中 [複製方法](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)）。最後保存成需要的格式。

{{% blocks/products/pf/feature-page-code h3="Java 拆分 Excel 文件的代碼" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 工作表拆分為窗格" %}}

API 還提供將 Excel 工作表拆分為不同窗格的功能。過程是，使用 Workbook 類加載文件。通過提供其索引來選擇第一個工作表或任何所需的工作表。調用具有相關小區索引的 setActiveCell 作為參數。最後通過調用 split() 方法將工作表窗口拆分為不同的窗格。

{{% blocks/products/pf/feature-page-code h3="Java 將 Excel 工作表拆分為窗格視圖的代碼" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
