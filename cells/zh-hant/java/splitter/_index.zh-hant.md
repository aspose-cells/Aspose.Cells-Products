---
title: 將 Excel 電子表格拆分為 Java 中的工作表
description: Java 源代碼，解釋如何使用 Java Excel 庫將 Microsoft Excel 文件拆分為多個文檔
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 文件分割 via Java" h2="在基於 Java 的應用程序中將 Excel 電子表格拆分為工作表" >}}
{{% blocks/products/pf/feature-page-summary %}}
有多種場景，當需要拆分 Excel 文件（例如包含學生數據的電子表格）並為每個學生分配單個工作表時。並且需要將每個學生的工作表拆分為一個單獨的文件。要自動化它 via Java 應用程序，[Java Excel API](/cells/zh-hant/java/)是否可以按工作表拆分 Excel 文檔。支持的格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 文檔拆分為多個文件" %}}

將 Excel 文件拆分為工作表的最簡單方法是訪問所有工作表，遍歷每個工作表並以所需格式一張一張保存。為了加載工作表，API 提供[練習冊](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)班級。[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count)方法獲取總頁數。迭代每個工作表並使用[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get)用於訪問特定工作表。使用以下命令將選定的工作表數據移動到新創建的 Workbook 類對像中[複製方法](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)）。最後保存成需要的格式。

{{% blocks/products/pf/feature-page-code h3="Java 分割Excel文件的代碼" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 工作表拆分為多個窗格" %}}

API還提供了將Excel工作表拆分為不同窗格的功能。過程是，使用 Workbook 類加載文件。通過提供其索引來選擇第一個工作表或任何所需的工作表。調用具有相關單元格索引作為參數的setActiveCell。最後通過調用 split() 方法將工作表窗口拆分為不同的窗格。

{{% blocks/products/pf/feature-page-code h3="Java 將 Excel 工作表拆分為窗格視圖的代碼" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
